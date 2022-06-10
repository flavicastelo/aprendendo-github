# Comandos úteis
* `git status` -> verifica o status do projeto, se precisa adicionar na stage, commitar, etc.
* `git log` -> verifica os commits e mostra os ID (apertar a tecla 'q' para sair)
* `git diff` -> mostra as modificações do arquivo (só funciona antes de mandar o arquivo para stage)
* `git reset`-> tira o arquivo da stage
* `git checkout - ` -> volta para branch anterior, útil para ficar alternando entre 2 branches
* `git checkout -b nomeDaBranch` -> cria nova brach e já muda para ela
&nbsp;
---
#### Stash
Não pode mudar de branch sem commitar a alteração, mas se não quiser commitar ainda, pode armazenar a alteração temporariamente usando o **stash**
* `git stash` -> armazena temporariamente as alterações do arquivo
* `git stash --include-untracked` -> armazena todos os arquivos novos da branch
* `git stash list` -> onde estão armazenada as alterações
* `git stash apply`-> para aplicar as alterações (tirar do armazenamento temporário)
* `git stash clear` -> limpa a list
