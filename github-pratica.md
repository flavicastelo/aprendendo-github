# APRENDENDO A UPAR O PROJETO PARA O GITHUB
## Passo a passo

### Criando o projeto
**No Computador**
1. Entra no repositório
2. Cria a branch main -> `git branch main`
3. Entra na branch main -> `git checkout main`
4. `git init` -> para inicializar o git
5. `git config --global user.name "nome"` 
6. `git config --global user.email "email"`
7. `git add .` -> para adicionar todos os arquivos na stage
8. `git commit -m "msg"` -> para commitar 

**No Github**
1. Cria um repositório:
    - *Your repositories > New*
2. `git remote add origin linkdorepo`
3. `git push -u origin main` -> -u no primeiro push serve para armazenar o remote e a branch
    - *caso dê erro tentar usar o `git pull origin main`*


### Atualizando o projeto
**No Computador**
1. `git add .` -> para adicionar todos os arquivos na stage
2. `git commit -m "msg"` -> para commitar 
3. `git push`

### Comandos úteis
* `git status` -> verifica o status do projeto, se precisa adicionar na stage, commitar, etc.
* `git log` -> verifica os commits e mostra os ID (apertar a tecla 'q' para sair)
* `git diff` -> mostra as modificações do arquivo (só funciona antes de mandar o arquivo para stage)
* `git reset`-> tira o arquivo da stage

### Observações
* `git clone`x `git pull`
    - Quando não tenho o projeto na máquina local -> `git clone`
    - Quando preciso pegar apenas as novas alterações que ocorreram no projeto -> `git pull`