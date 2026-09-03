# 📚 API de Livros

<p align="center">
  <strong>API REST para gerenciamento de livros</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-1F3A5F?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-0F4C5C?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-8B4513?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/SQLAlchemy-9A3412?style=for-the-badge&logo=sqlalchemy&logoColor=white">
</p>

---

## 👩‍💻 Desenvolvedora

**Nome:** Lorena Silva

---

## 📖 Sobre o projeto

A **API de Livros** é uma aplicação desenvolvida em **Python** utilizando o framework **FastAPI**, com o objetivo de realizar o gerenciamento de informações relacionadas a livros.

A API permite que aplicações possam **cadastrar, consultar, atualizar e excluir livros**, utilizando requisições HTTP para realizar a comunicação com o sistema.

Os dados dos livros são armazenados em um banco de dados **MySQL**, enquanto o **SQLAlchemy** é utilizado para facilitar a comunicação entre a aplicação e o banco de dados.

---

## 🎯 Objetivo

O principal objetivo do projeto é desenvolver uma API funcional para gerenciamento de livros, aplicando conceitos de:

* Desenvolvimento de APIs REST;
* Requisições HTTP;
* Banco de dados relacionais;
* Integração entre Python e MySQL;
* Manipulação e validação de dados;
* Operações CRUD;
* Organização de aplicações back-end.

O projeto também possui finalidade **educacional**, permitindo compreender como diferentes tecnologias podem trabalhar em conjunto na construção de uma aplicação.

---

## 📚 Informações dos livros

Cada livro poderá possuir informações como:

| Campo                 | Descrição                         |
| --------------------- | --------------------------------- |
| **ID**                | Identificador único do livro      |
| **Título**            | Nome do livro                     |
| **Autor**             | Autor responsável pela obra       |
| **Ano de publicação** | Ano em que o livro foi publicado  |
| **Disponibilidade**   | Indica se o livro está disponível |

---

## 🔌 Funcionalidades

A API será responsável pelas principais operações de gerenciamento de livros:

### 🟧 Criar

Permite cadastrar um novo livro no sistema.

### 🔵 Consultar

Permite visualizar os livros cadastrados e consultar informações de um livro específico.

### 🟧 Atualizar

Permite modificar informações de um livro já cadastrado.

### 🔴 Excluir

Permite remover um livro do sistema.

Essas funcionalidades correspondem às operações conhecidas como **CRUD**:

> **C**reate → Criar
> **R**ead → Consultar
> **U**pdate → Atualizar
> **D**elete → Excluir

---

## 🌐 Rotas da API

A API utiliza diferentes rotas para realizar suas operações:

| Método   | Rota           | Função                        |
| -------- | -------------- | ----------------------------- |
| `POST`   | `/livros`      | Cadastrar um livro            |
| `GET`    | `/livros`      | Listar livros                 |
| `GET`    | `/livros/{id}` | Consultar um livro específico |
| `PUT`    | `/livros/{id}` | Atualizar um livro            |
| `DELETE` | `/livros/{id}` | Excluir um livro              |

---

## 🛠️ Tecnologias utilizadas

### 🐍 Python

Linguagem de programação utilizada no desenvolvimento da aplicação.

### ⚡ FastAPI

Framework utilizado para construir a API e suas rotas HTTP.

### 🚀 Uvicorn

Servidor utilizado para executar a aplicação FastAPI.

### 🗄️ SQLAlchemy

Biblioteca responsável por facilitar a comunicação entre o código Python e o banco de dados.

### 🔌 PyMySQL

Driver utilizado para realizar a conexão da aplicação Python com o MySQL.

### ⚙️ Pydantic Settings

Utilizado para trabalhar com configurações e dados da aplicação.

### 🐬 MySQL

Sistema de gerenciamento de banco de dados relacional utilizado para armazenar as informações dos livros.

---

## 🔄 Funcionamento da aplicação

O funcionamento da API ocorre através da comunicação entre o cliente, a aplicação e o banco de dados.

```text
┌──────────────────┐
│      CLIENTE     │
│ Navegador / App  │
└────────┬─────────┘
         │
         │ Requisição HTTP
         ▼
┌──────────────────┐
│     FASTAPI      │
│     REST API     │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│    SQLALCHEMY    │
│ Acesso aos dados │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│      MYSQL       │
│ Banco de dados   │
└──────────────────┘
```

Quando uma aplicação realiza uma requisição, o **FastAPI** recebe essa solicitação, processa os dados e utiliza o **SQLAlchemy** para acessar o **MySQL** quando necessário.

Depois do processamento, a API retorna uma resposta ao cliente.

---

## 📦 Arquitetura da aplicação

A separação das tecnologias permite organizar melhor as responsabilidades:

**FastAPI**
Responsável pelas requisições e respostas da API.

**SQLAlchemy**
Responsável pela comunicação e manipulação dos dados.

**MySQL**
Responsável pelo armazenamento permanente das informações.

Essa divisão facilita a manutenção e permite compreender melhor o funcionamento de uma aplicação back-end.

---

## 🧠 Conceitos aplicados

Durante o desenvolvimento da API são trabalhados conceitos importantes de programação e desenvolvimento web, como:

* APIs REST;
* HTTP;
* JSON;
* CRUD;
* Rotas;
* Métodos HTTP;
* Banco de dados;
* SQL;
* ORM;
* Validação de dados;
* Integração entre sistemas;
* Back-end.

---

## 🚀 Futuras implementações

O projeto poderá ser expandido futuramente com novas funcionalidades, como:

* 🔎 Pesquisa de livros;
* 📑 Paginação dos resultados;
* 👤 Cadastro de usuários;
* 🔐 Sistema de autenticação;
* ⭐ Avaliação de livros;
* 📚 Categorias e gêneros;
* 🔍 Filtros de pesquisa;
* 🖥️ Interface web para utilização da API.

---

## 📌 Resumo

A **API de Livros** é um projeto back-end desenvolvido com **Python e FastAPI**, integrado ao **MySQL** através do **SQLAlchemy**.

Seu objetivo é disponibilizar uma estrutura para **gerenciar livros por meio de uma API REST**, permitindo realizar operações de cadastro, consulta, atualização e exclusão.

O projeto demonstra, de forma prática, como uma aplicação pode receber requisições, processar informações, acessar um banco de dados e devolver respostas para outras aplicações.

---

<p align="center">
  <strong>📚 API de Livros</strong>
  <br>
  <sub>Python • FastAPI • SQLAlchemy • MySQL</sub>
</p>
