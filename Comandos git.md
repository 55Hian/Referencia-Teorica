# Comandos Linux

## pwd
#### mostra diretório atual

## cd
#### navega entre pastas

## mkdir
#### Cria uma nova pasta dentro do diretório atual

# Comandos Git
#### tudo entre angle brackts (<>) são de acordo com o dev.

## Git -v
#### Mostra a versão do git

## git init
#### inicia o git no repositorio atual 

## git branch
mostra branchs existentes

## git branch < nome branch >
#### cria uma nova branch 

## git branch -d < nome branch > 

## git config user.name "Hian"
### git config --global user.name "nome"

## git config user.email "email"
### gir congig --global user.email "global"

## Git-add
#### adiciona um arquivo ao git (preparação para o commit)

## Git-commit
#### "Fecha a caixa" de arquivos para serem enviados ao repositório.

## Git switch <seu branch> 
#### Muda o branch 

## git switch -c "nome"
#### cria e muda para o branch

## Git checkout <seu branch> 
#### informa o branch atual e muda o branch

## Git tag -a <v0.1.0> -m "tag do lançameno"
#### vercionamento do código com tag
### regras de versão:
#### x.y.z: 
#### x = quando a nova aplicação não é compativel com a anterior (necessario reinstalar o app)
#### y = quando uma nova funcionalidade é adicionada ao app
#### z = quando um bug é corrigido

## Git tag -d <v0.1.0>
#### Deleta versão criada

## Git commit -m "mensagem do commit" --allow-empty 
#### sobe commit mesmo sem alterações

## Git tag
#### mostra as versões de codigo

## git push --set-upstream origin < Desenvolvimento >
#### Envia um branch para o repositório remoto

## git push origin --delete fix-margins
#### deleta um branch do repositorio remoto

## git push --tags
#### Envia as tags para o repositório remoto

## git log --decorate --graph --all
#### mostra arvore de commits do processo

## git branch -f "branch escolhido" "branch destino"
#### muda um branch parar qualquer posição na arvore

## git cherry-pick <Commit1> <Commit2> <...>
#### cria copias de commit em um novo ramo

## git rebase -i
#### cria copias de commit em um novo ramo de forma interativa (interface)

## git commit --amend

# Bibiografia:
## https://developer.mozilla.org/pt-BR/docs/Glossary/WHATWG
#### Tags html mozilla

## https://www.w3schools.com/tags/
#### Tags html ww3

## https://meyerweb.com/eric/tools/css/reset/
#### Codigo reset para css

## https://learngitbranching.js.org/?locale=pt_BR
#### Treinamento git branch

## https://color.adobe.com/pt/create/color-wheel
#### Paleta de cores

# Siglas:
## SEO - Search Engine Optimization
## RFC - Request for commit

ipconfig - mostra dados da rede do computador (ip)

ping < ip do equipamento ou link do site> - manda uma solicitação de ping e aguarda retorno 

NS - Name System
DNS - Domain Name System

tracert link do site - mostra rota até chegar no site.

#CSS
organização do margin e paddin: Topo Direita Fundo Esquerda