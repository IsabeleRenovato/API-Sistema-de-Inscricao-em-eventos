# 🚀 NLW Connect - Java

Este repositório contém os aprendizados e a aplicação desenvolvida durante o evento **NLW Connect**, promovido pela **Rocketseat**.

## 📌 Sobre o NLW

O **Next Level Week (NLW)** é uma imersão intensiva de uma semana, repleta de código, desafios e networking, proporcionando uma experiência prática e enriquecedora.

## 🖥️ Trilha Java com Spring Boot

Na trilha de **Java**, conduzida pelo professor **Isidro**, desenvolvi uma aplicação completa para **inscrição em eventos**, explorando conceitos fundamentais do **ecossistema Java e Spring Boot**.

## 🔧 Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **Spring Initializr**
- **Spring Data JPA**
- **Maven**
- **MySQL Workbench**
- **Docker (para rodar o banco de dados)**
- **Postman (para testes das APIs)**

## 📚 O que foi desenvolvido?

- Configuração do ambiente de desenvolvimento.
- Utilização do **Spring Initializr** para estruturar o projeto.
- Integração com o banco de dados **MySQL**.
- Implementação de funcionalidades como:
  - **Cadastro e recuperação de eventos** (por ID e URL).
  - **Modelagem de entidades** para inscrição de usuários.
  - **Validação de regras de negócio**.
  - **Geração de relatórios**, incluindo:
    - Número de inscritos.
    - Inscrições por indicação.
    - Ranking de usuários.


## 📂 Estrutura do Projeto

NLW-Connect-Java

│── src/main/java/br/com/nlw/events

│   ├── controller   ----  # Controllers da API

│   ├── dto   ----   # Data Transfer Objects (DTOs)

│   ├── exception     ---       # Classes para tratamento de exceções

│   ├── model      ---          # Entidades do banco de dados

│   ├── repository     ---      # Repositórios (Spring Data JPA)

│   ├── service       ---       # Regras de negócio

│── src/main/resources
│   ├── application.properties  --- # Configuração do banco de dados

└──  pom.xml        ---         # Gerenciamento de dependências (Maven)


