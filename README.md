# To-Do List API

Este é um projeto de API REST para gerenciar uma lista de tarefas, construído usando Java 17, Spring Boot 3, Spring Data JPA, e H2 Database. A API permite criar, ler, atualizar e excluir tarefas, e inclui documentação interativa usando Swagger.
Criado como desafio para o curso Dio + Santander

## Tecnologias Utilizadas

- **Java 17**: Linguagem de programação usada para implementar a API.
- **Spring Boot 3**: Framework para criar aplicativos baseados em Spring com configuração automática.
- **Spring Data JPA**: Biblioteca para acesso a dados e manipulação de entidades JPA.
- **H2 Database**: Banco de dados em memória usado para armazenar tarefas.
- **Swagger**: Ferramenta para documentação interativa da API.
- **GitHub Actions**: Automatização do deploy no Railway.

## Funcionalidades

- **Listar Tarefas**: `GET /todos` - Retorna todas as tarefas.
- **Obter Tarefa por ID**: `GET /todos/{id}` - Retorna uma tarefa específica.
- **Criar Tarefa**: `POST /todos` - Adiciona uma nova tarefa.
- **Atualizar Tarefa**: `PUT /todos/{id}` - Atualiza uma tarefa existente.
- **Excluir Tarefa**: `DELETE /todos/{id}` - Remove uma tarefa específica.

## Configuração do Projeto

### Pré-requisitos

- [Java 17](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)
- [Git](https://git-scm.com/)

