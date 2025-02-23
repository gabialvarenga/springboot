# Curso de Spring Boot - Rocketseat DevStage  

## Descrição  
Este repositório contém o projeto desenvolvido durante o curso de **Spring Boot** da **Rocketseat DevStage**. O objetivo do projeto é criar um **software de indicação para eventos online**, permitindo que usuários se inscrevam, indiquem amigos e acompanhem estatísticas em tempo real.  

A aplicação oferece funcionalidades essenciais para a gestão de eventos, como **cadastro de eventos**, **inscrição de usuários**, **validação de regras de negócio**, **geração de relatórios** e um **ranking de indicações**.  

## Sumário  

- [Descrição do Projeto](#descrição-do-projeto)  
- [Tecnologias Utilizadas](#tecnologias-utilizadas)  
- [Funcionalidades](#funcionalidades)  
- [Configuração do Ambiente](#configuração-do-ambiente)  
- [Conexão com o Banco de Dados](#conexão-com-o-banco-de-dados)  
- [Educador da Trilha](#educador-da-trilha)  

---

## Descrição do Projeto  

Este projeto tem como objetivo desenvolver uma aplicação que permita a **inscrição em eventos**, gerenciando **usuários** e **eventos** de forma eficiente.  

Ao longo do curso, foram abordados conceitos fundamentais do **ecossistema Java e Spring Boot**, incluindo:  

- **Configuração do ambiente de desenvolvimento**;  
- **Criação do projeto utilizando o Spring Initializr**;  
- **Conexão da aplicação a um banco de dados MySQL** com **Spring Data JPA**;  
- **Implementação de operações essenciais**, como **cadastro e recuperação de eventos por ID e URL**;  
- **Modelagem de entidades** para **inscrição de usuários e registro de indicações**;  
- **Validação de regras de negócio** para garantir integridade e segurança dos dados;  
- **Geração de relatórios** com informações detalhadas, como **número total de inscritos, inscrições por indicação e ranking de usuários mais ativos**.  

---

## Tecnologias Utilizadas  

- **Java**  
- **Spring Boot**  
- **Spring Web** (API REST)  
- **Spring Data JPA**  
- **Hibernate**  
- **Lombok**
- **MySQL** (banco de dados)  
- **Maven** (gerenciador de dependências)  

---

## Funcionalidades  

- **Cadastro de eventos**  
- **Recuperação de eventos por ID e URL**  
- **Modelagem de entidades para inscrição de usuários**  
- **Validação de regras de negócio** para garantir integridade e segurança  
- **Geração de relatórios**, incluindo:  
  - **Número total de inscritos**  
  - **Inscrições realizadas por indicação**  
  - **Ranking de usuários com mais indicações**  

---

## Configuração do Ambiente  

Antes de rodar o projeto, é necessário configurar o ambiente de desenvolvimento:  

- **Instalar o JDK 17+**  
- **Instalar o MySQL Server**  
- **Configurar uma IDE** como **IntelliJ IDEA** ou **VSCode** para facilitar o desenvolvimento  
- O projeto foi inicializado com o **Spring Initializr** utilizando as dependências **Spring Web**, **Spring Data JPA**, **MySQL Driver** e **Lombok**

---

## Conexão com o Banco de Dados    

A configuração do banco deve ser feita no arquivo `application.properties`:  

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect
```

## Educador da Trilha

**Professor Isidro**

---

Sinta-se à vontade para contribuir com melhorias ou relatar problemas através das issues neste repositório!
