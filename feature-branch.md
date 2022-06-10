# Testando a Feature Branch

**No Computador**
* `git checkout -b nomeBranch` ->cria uma brach e entra nela
* `git add nomeArquivo` -> adiciona na stage
* `git commit -m "msg"` -> commmita
* `git push origin nomeBranchNova`

**No github**
* Pull request > new
* Base: branch para onde quer mandar o pull e Compare: branch que vai mandar o pull
* Em **Reviewers** adiciona os revisores
* Create Pull Request
* Após aprovação na aba Conversation:
    - Merge pull request
    - Commit msg
* Deleta a branch

**No Computador**
* Volta para branch principal -> `git checkout nomeBranch`
* `git merge nomeBranchSec` -> para pegar as modificações da branch secundária
* Deleta a branch secundária -> `git branch -D nomeBranchSec`
* `git pull origin main` -> para atualizar a branch
* `git add .` -> adiciona os arquivos na stage
* `git commit -m "msg"`

