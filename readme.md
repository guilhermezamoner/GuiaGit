### Guia com os mais frequentes comandos no git

#### Iniciar um novo repositório :
* git init

#### Clonar repositório remoto :
* git clone link-repo

#### Adicionar mudanças realizadas :
* git add <arquivo>
* Para múltiplos : git add .

#### Desfazer alteração de arquivo :
* git checkout nome_arquivo
* Para múltiplos : git checkout .

#### Realizar commit da alteração :
* git commit -m " descricao da alteracao"

#### Enviar alterações do repositorio local para o remoto :
* git push origin "nomebranch"

#### Caso queira conectar o repositorio local a um servidor remoto :
* git remote add origin <server>

#### Criar branch 
* git branch "Nomebranc"

#### Deletar branch 
* git branch -d "NomeBranch"

#### Ir de um branch para o outro
* git checkout "nomebrancdesejado"

#### Atualizar branch local, para receber o que está no remoto :
* git pull origin "nomebranch"

#### Mesclar conteudo de branchs :
* git merge "nomebranch"

#### Diferenciar branchs
* git diff master homologation 
##### Observação: Git diff pode ser usado também para comparar arquivos de branchs distintos, para isso basta só passar como parâmetro o caminho com o diretório do arquivo

#### Listagem dos Commits :
* git log

### Stash p/ untracked files :

* git stash --include-untracked 


##### Para visualizar os commit's com maior facilidade, basta utilizar o GitK.
