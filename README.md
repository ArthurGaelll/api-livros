# 📚 API de Livros

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</p>

<p align="center">
  Projeto escolar de desenvolvimento de uma API REST de livros com CRUD completo.
</p>

---

## 📖 Sobre o projeto

Este projeto consiste na criação de uma **API de Livros**, desenvolvida em **Python utilizando FastAPI**, com integração a um banco de dados **MySQL**.

A aplicação terá um **CRUD completo**, permitindo realizar as principais operações sobre os livros:

- 🟢 **Create** → Cadastrar livros
- 🔵 **Read** → Listar e consultar livros
- 🟠 **Update** → Atualizar livros
- 🔴 **Delete** → Excluir livros

Além do desenvolvimento da API, o projeto contará com uma **interface web utilizando HTML, CSS e JavaScript**, que irá consumir a API através do método `fetch()`.

O projeto será desenvolvido em etapas, permitindo acompanhar toda a sua evolução através do **Git e GitHub**.

---

# 🔄 CRUD

| Símbolo | Operação | Método HTTP | Ação |
|:---:|:---:|:---:|:---|
| 🟢 | **Create** | `POST` | Cadastrar livros |
| 🔵 | **Read** | `GET` | Listar e consultar livros |
| 🟠 | **Update** | `PUT` | Atualizar livros |
| 🔴 | **Delete** | `DELETE` | Excluir livros |

---

# 🎯 Objetivos

O projeto tem como objetivo colocar em prática os seguintes conhecimentos:

- Criar rotas utilizando **FastAPI**
- Utilizar os métodos HTTP **GET, POST, PUT e DELETE**
- Conectar Python a um banco de dados **MySQL**
- Utilizar **XAMPP** e **phpMyAdmin**
- Criar **Models e Schemas**
- Validar dados recebidos pela API
- Tratar erros HTTP
- Construir interfaces utilizando **HTML, CSS e JavaScript**
- Consumir uma API utilizando `fetch()`
- Utilizar o **Source Control do VS Code**
- Utilizar **Git e GitHub**
- Registrar a evolução do projeto através de commits

---

# 🛠️ Tecnologias utilizadas

### 💻 Backend

- 🐍 Python
- ⚡ FastAPI
- 🚀 Uvicorn
- 🗃️ SQLAlchemy
- 🔌 PyMySQL

### 🗄️ Banco de dados

- 🐬 MySQL
- 🟧 XAMPP
- 🛠️ phpMyAdmin

### 🎨 Frontend

- 🌐 HTML5
- 🎨 CSS3
- ⚡ JavaScript

### 🔧 Ferramentas

- 💻 Visual Studio Code
- 🌱 Git
- 🐙 GitHub

---

# 🏗️ Estrutura do projeto

A estrutura planejada para o projeto será:

```text
API-LIVROS/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   │
│   └── routes/
│       └── livros.py
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── .gitignore
├── requirements.txt
└── README.md
