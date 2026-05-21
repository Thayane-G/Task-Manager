# Task Manager

Esse foi um projeto que desenvolvi para praticar Java com integração ao MySQL utilizando JDBC.

A ideia foi criar um sistema simples de gerenciamento de tarefas funcionando pelo terminal, colocando em prática operações CRUD e melhorando minha organização de código no back-end.

# Funcionalidades

Cadastrar tarefas
Listar tarefas
Atualizar status
Excluir tarefas

#Tecnologias utilizadas

Java
MySQL
JDBC
Git/GitHub

#Estrutura do projeto

src/
├── connection/
├── dao/
├── model/
└── App.java

# Banco de dados

CREATE DATABASE task_manager;

USE task_manager;

CREATE TABLE tasks (

    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(100),
    description VARCHAR(255),
    status VARCHAR(50)

);

#Como executar

1 - Clone o repositório --> git clone https://github.com/seu-usuario/task-manager-java.git
2 - Configure a conexão com o MySQL no ConnectionFactory.java
3 - Execute o App.java

# O que aprendi com esse projeto

Durante o desenvolvimento consegui praticar:

CRUD
JDBC
integração Java + MySQL
organização em camadas
DAO
orientação a objetos

Além disso, também foi um projeto importante para me familiarizar melhor com versionamento utilizando Git e GitHub.

# Autora

Thayane Gabriele.
