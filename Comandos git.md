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


## Git-add
#### adiciona um arquivo ao git (preparação para o commit)

## Git-commit
#### "Fecha a caixa" de arquivos para serem enviados ao repositório.

## Git switch <seu branch> 
#### Muda o branch 

## Git checkout <seu branch> 
#### informa o branch atual

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

## git push --set-upstream origin <Desenvolvimento>
#### Envia um branch para o repositório remoto

## git push --tags
#### Envia as tags para o repositório remoto
