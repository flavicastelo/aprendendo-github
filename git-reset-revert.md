# ME ARREPENDI DA ALTERAÇÃO E AGORA?
## Git reset x git revert

### Git reset
#### Voltar a versão anterior antes do commit
* Modifiquei o arquivo
* Mandei para stage -> `git add nomeArquivo`
* **Me arrependi da alteração**
    1. `git reset` -> tira da stage
    2. `git checkout nomeArquivo` -> volta o arquivo para versão anterior

#### Voltar a versão anterior depois do commit
* Modifiquei o arquivo
* Mandei para stage -> `git add nomeArquivo`
* Fiz o commit -> `git commit -m "msg"`
* **Me arrependi da alteração**
    1. `git log`-> pegar o id do commit anterior ao commit que me arrependi
    2. `git reset --soft/mixed/hard idCommit`
        * soft: volta o commit mantendo as modificações na stage
        * mixed: volta o commit mantendo as modificações na modified
        * hard: reseta total
&nbsp;
---
### Git revert
O *git revert* mantém o commit no histórico e cria um commit para o revert
* Modifiquei o arquivo
* Mandei para stage -> `git add nomeArquivo`
* Fiz o commit -> `git commit -m "msg"`
* **Me arrependi da alteração**
    1. `git log`-> pegar o id do commit que se arrependeu
    2. `git revert idCommit`

