# introdução a java
## o que é java?
#### é uma linguagem de programação, que funciona em diversos dispositivos sem necessariamente programar especificamente para cada um deles

## orientada a objeto
#### tudo com esessao dos tipos primitivos é orientado a objeto
#### tudo é escrito em termos de classes e objetos

## prefisa entender
#### classes e objetos
#### encapsulamento
#### abstração 
#### herança 
#### polimorfismo

## plataforma independente
#### funciona em qualquer plataforma (windows,apple, IOS, android, etc)

## interpretada ou compilada?
#### java utiliza os dois, é compilada para gerar um arquivo bytecode e a JVM interpreta o arquivo bytecode durante a execução 

# ambiente de desenvolvimento java
## IDE 
### Integrated Development Environment ou Ambiente de Desenvolvimento Integrado
#### auto-complete e intelliSense
#### formatação de palavras e blocos de cofigo
#### analise de erro de sintaxe
#### compilação de programas
#### depuração (acompanhamento) de execução do programa.

#### Eclipse IDE
ambiente corporativo 
#### IntelliJ
ambiente academico 
#### Visual Studio Code
pra quem já trabalha com outras plataformas 

#Ateção
### nome de projeto somente com as primeiras letras maiuscula
### nome de pacote todo minusculo
### nome de classe somente com as primeiras letras maiusculas
### nome de metodo todo minusculo

### sysout - atalho para System.out.println() no eclipse

### propriedade - variavel
### metodo - função

### uma classe é um conjunto de propriedades e metodos.
### main sempre é o primeiro metodo a ser executado
### arquivo .class é um txt, arquivo .java é binario
### classe de driver é aquela classe que tem o metodo main
### objetos são coisas com mesmas propriedades, em java, devem pertencer a mesma classe.
### https://docs.oracle.com/en/java/javase/17/docs/api/allclasses-index.html - sintaxe java

# Herança
### criar uma classe apartir de uma classe que ja existe
#### Qual vantagem?
#### economiza tempo durante o desenvolvimento do programa.
#### facilita a manutenção do sistema

#### a classe que ja existe é a super-classe (classe mae)
#### a nova classe é uma sub-classe (classe filho)
#### se você não der novos parametros, ela só copia o codigo da sua super-classe
#### uma subclasse pode ter seus proprios metodos e campos
#### a subclasse sempre é mais especifica que a superclasse


#### superclasse direta - esta logo acima de você
#### superclasse indireta - classes acima da sua super classe direta
#### a hierarquia de classes começa com a Object(fica em java.lang)
#### toda classe herda de object
#### java suporta apenas uma herança unica ( Super-classe --> sub-classe)

#### distinção entre relacionamentos

#### is-a (é um) 
#### has-a (tem um)

# Atributos protected
### 


empresa com dois tipos de funcionarios
funcionario 1 - se nao vender = 0, se vender = comissão
funcionario 2 - se não vender = fixo, se vender = comissão


