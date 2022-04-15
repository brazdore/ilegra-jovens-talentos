# ilegra-jovens-talentos

- Este repositório contém todos os projetos e atividades realizados por mim no programa de Jovens Talentos da ilegra.
- O programa foi dividido em três trilhas: Core Engineering, Cloud Native e DevOps.
- As instruções de cada atividade estão abaixo.
<hr/>

## Core Engineering

### Lean e Agile

#### Tema 2: Agile

```
Faça uma lista com todos os métodos ágeis, incluindo Scrum e XP e explique em 2 ou 3 linhas como eles funcionam:
Faça um texto de 3 – 5 linhas explicando os problemas com agile:
Qual a relação entre Agile/Lean e Bi Modal e DevOps?
```

### OOP

#### Tema 3: override/overload

```
Fazer um texto explicando o que é override e overloading
Enviar via PR
```

### Java

#### Tema 4: Multithreading

```
Criar um programa que use duas threads
A thread A irá gerar apenas números randômicos ímpares e irá printá-los no console. Essa thread deve printar um número a cada 100 milisegundos
A thread B irá gerar apenas números randômicos pares e irá printá-los no console. Essa thread deve printar um número a cada 500 milisegundos
Use a classe main para instanciar e iniciar as Threads
```

### Testes

#### Tema 5: Lampada

```
Criar um projeto java com gradle
Esse projeto deverá tem  uma Interface Lampada com a assinatura dos método void on(); e void off().
Criar duas classe que implementam essa interface
Criar uma classe que recebe uma lâmpada pelo construtor e expor um método void switchState()
Na classe main, exemplificar o exercício
Testar o método switchState para cada cenário ON e OFF
Testar a classe que tem o método switch com cada uma das classes que implementam a interface Lampada
Observação: utilizar JUNIT5
```

### Clean Code

#### Tema 6: Agenda de contatos

```
Criar um projeto de agenda de contato
Deve ser possível adicionar contato, remover contato, listar contato, buscar por nome, buscar por id.
Não utilizar banco de dados e nem arquivos. Usem um array em memória.
Adicione testes unitários para cada operação
Fazer PR
```

### TDD

#### Tema 7: TDD

```
Criar um conversor de números romanos para números inteiros
Deve suportar números de 1 a 20
Deve ser possível passar um numero romano e convertê-lo para inteiro
Deve ser possível também passar um numero inteiro e converte-lo para romano
Deve ser desenvolvido utilizando TDD. Testes primeiro.
```

### Philosophy of Software Design

#### Tema 8: Biblioteca

```
Fazer uma aplicação de empréstimo livro
Deve ser possível
Cadastrar livro (id, titulo, autor)
Listar livro
Excluir (não pode excluir um livro que está emprestado)
Buscar por título ou por autor
Empréstimo de livro
Uma pessoa pode fazer empréstimo de no máximo 5 livros
Prazo de entrega é 7 dias
Uma pessoa pode devolver vários livros
Uma pessoa pode renovar um livro por mais 7 dias, exceto se ela estiver atrasada
No momento da devolução será cobrado 5 reais por dia de atraso
Exibir relatório de livros emprestados e nome da pessoa que estiver com ele
Exibir os TOP 10 usuários que mais locam livros
Exibir relatórios do cliente que atrasaram a entrega e quantos dias de atraso
Independente da abordagem TDD ou testes depois, deve ter testes
Não pode ter banco de dados, salvar tudo em arquivo
```

### DDD

#### Tema 9 : DDD

```
Responder as seguintes questões:
Qual é o objetivo principal do DDD?
Qual é o impacto que DDD pode causar no projeto?
```

### Banco de dados

#### Tema 10: Agenda de contato + banco de dados

```
Criar um projeto de agenda de contato (id, nome, telefone, email)
Deve ser possível adicionar contato, remover contato, listar contato (ordenar por nome/id), buscar por nome, buscar por id.
Todas as operações devem envolver banco de dados.
Fazer PR
```

### Design Pattern (criacionais)

#### Tema 11: Factory

```
Implementar o padrão de projeto Factory com tema livre
```

#### Tema 12: Builder

```
implementar builder com interface fluente
Crie uma classe Pessoa (nome, data de nascimento, endereço),
Crie uma classe endereço (rua, número, cidade, estado)
Crie uma classe builder com interface fluente para fazer a criação de uma pessoa completa.
```

### Design Pattern (comportamentais)

#### Tema 13: Strategy

```
Criar um sistema de envio notificação que suporta apenas SMS e Email (apenas escrever no terminal o tipo de notificação junto com a mensagem)
Deve existir uma classe que represente um cliente apenas com nome,email e telefone.
Deve existir uma classe responsável por apenas montar uma mensagem(Hello + nome do cliente) e usar uma classe de notificação para enviar.
Utilizar o padrão Strategy para definir SMS e Email.
Regra: o sistema deve validar se o cliente possui  telefone preenchido enviar por telefone caso contrario enviar por email(email é obrigatório).
```

#### Tema 14: Template method

```
criar um sistema responsável por fazer bebida quentes
criar uma abstração para definir os métodos necessários(abstratos) para criar uma bebida quente e um método(concreto) responsável por executar em ordem
Criar duas classes para criar bebidas quente .
```

#### Tema 15: Chain

```
Crie uma classe abstrata NotificationHandler
Crie 3 implementações dessa classes(Exemplo: EmailNotificationHandler)
Crie uma classe Request
A partir de uma request pode executar mais de um elemento da chain
```

#### Tema 16: Command

```
Crie um sistema de banco onde é possível apenas depositar dinheiro e sacar dinheiro
Essas duas ações devem utilizar o design pattern command
Deve ser possível salvar o histórico os commands executados, usem um arraylist static
Deve existir consulta de saldo que irá ler todos os commands para calcular o saldo
```

### Design Pattern (estruturais)

#### Tema 17: Decorator

```
Crie uma classe que será a base de uma pizza (preço 20 reais)
Crie um decorador para adicionar queijo (preço 3 reais)
Crie um decorator para adicionar bacon (preço 3,5)
No main, use as classe criadas para montar uma pizza de bacon com o dobro de queijo. Qual é o valor da pizza?
```

<hr/>

## Cloud Native

### Spring Framework

#### Tema 1 - Calculadora com spring

```
1) Criar calculadora com anotações
 cada função modular
 operações SUM/SUB/MULTIPLY/DIVISION/POW
 Histórico
2) Validações
3) Fazer testes
```

### Cloud Native Review / Guice / Tomcat / Jetty

#### Tema 2 - Petstore Guice

```
Create a petstore providing:
 Add pets(id, name, race, age)
Remove pet’s(id)
Search pet by Age
doBath(id) with or without perfume / dry or water
doHairCut(id) short or long
history services
top 10 pets revenue
```

#### Tema 3 - Tomcat

```
Choose the petstore or calculator to deploy on Tomcat.
The steps to run the application must be on readme file.
```

#### Tema 4 - Jetty

```
Choose the petstore or calculator to deploy on Jetty.
The steps to run the application must be on readme file.
```

### SOA Principles

### Rest

#### Tema 5 - Pedágio Rest

```
Criar um sistema de pedagio usando REST
onibus 1,59
moto 1
bike 49
caminhão 3,95
Fusca 2,11
Pagamento: Deve receber um valor e retornar o troco. Caminhão deve cobrar adicional por eixo.
Listar a tabela de preços do pedágio
```

### Docker

#### Tema 6 - Containerizar a calculadora

```
Criar um container docker com a aplicação da calculadora desenvolvidas e acessar a mesma pelo browser.
```

#### Tema 7 - Criar microservices

```
Criar microservice que pelo user busca o total de tweet (usar api twitter)
Criar microservice que pelo user busca o total de repositórios no Github(usar api github)
Criar microservice que recebe usuario twitter e usuario do github e retorno os totalizadores (chamar os outros serviços)
Rodar tudo dentro de containers docker
Utilizar SpringBoot
```

### Rx and RxNetty

#### Tema 8 - RX and RxNetty

```
Migrar a calculadora para Karyon RxNetty
Rodar em container
```

### NetflixOss Stack

#### Tema 9 - Microservicos

```
implementar POW microservice
https://github.com/diegopacheco/netflixoss-pocs/tree/master/netflixoss-microservices
```

### Hystrix, Dasboard and NoSql

#### Tema 10 - hystrix

```
Adicionar hystrix e o dashboard no tema do springboot
Não utilizar SpringCloud!
```

## Temas Finais de Cloud Native

### [Tema Final #1](2-cloud-native/temas/tema_final_1.pdf)

### [Tema Final #2](2-cloud-native/temas/tema_final_2.pdf)

<br>
<hr/>

## DevOps

### 01 - [DevOps Culture Principles](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/1-DevOps.Culture.Principles/1-DevOps.Culture.Principles.txt)

### 02 - [SOA Microservices Cloud-Native](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/2-SOA.Microservices.Cloud-Native/2-SOA.Microservices.Cloud-Native.txt)

### 03 - [Linux](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/3-Linux/3-Linux.txt)

### 04 - [Bash](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/4-Bash/4-Bash.txt)

### 05 - [Python](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/5-Python/5-Python.txt)

### 06 - [Go lang](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/6-Go/6-Go.txt)

### 07 - [Docker](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/7-Docker/7-Docker.txt)

### 08 - [Vagrant](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/8-Vagrant/8-Vagrant.txt)

### 09 - [Ansible](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/9-Ansible/9-Ansible.txt)

### 10 - [Packer](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/10-Packer/10-Packer.txt)

### 11 - [Terraform](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/11-Terraform/11-Terraform.txt)

### 12 - [Jenkins](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/12-Jenkins/12-Jenkins.txt)

### 13 - [AWS](https://github.com/ilegra/DevOpsEngineerExpress/blob/master/homework/13-AWS/13-AWS.txt)
