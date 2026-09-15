# Distribuidora — Delivery Management System

> Terminal-based order and delivery management system backed by a MySQL relational database.

<div align="right"><a href="#english">🇬🇧 English</a> · <a href="#português">🇧🇷 Português</a></div>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

## English

### About

A terminal application that manages the day-to-day operation of a distributor.
Employees register orders, and the system tracks deliveries and the drivers
responsible for carrying them out. The relational schema was designed in MySQL
Workbench, and the application layer — written in Python — connects to the
database to run all operations. Deliveries are the core of the project.

### Features

- Register and manage orders placed by employees
- Track deliveries and the drivers assigned to each one
- Relational data model with foreign-key relationships between employees, orders, deliveries and drivers
- Results displayed as formatted tables in the terminal

### Tech Stack

**Python** · **MySQL** · `mysql-connector-python` · `tabulate`

### Data Model

The database is modeled in `sqldistribuidora.mwb` (MySQL Workbench) and created
from `Distribuidora_TrabF.sql`. An overview of the schema is in `foto.png`.

### Getting Started

**Prerequisites:** Python 3.x and a running MySQL Server.

```bash
# 1. Clone the repository
git clone https://github.com/Myrodian/Trab_Distribuidora.git
cd Trab_Distribuidora

# 2. Create the database (run the SQL script in MySQL)
mysql -u root -p < Distribuidora_TrabF.sql

# 3. Install the dependencies
pip install mysql-connector-python tabulate

# 4. Run the application
python distribuidora/main.py
```

> Before running, update the database connection settings (host, user, password)
> in the source code to match your local MySQL setup.

### What I practiced

Relational schema design, SQL (DDL/DML), connecting an application to a
relational database, and CRUD operations over related tables.

---

## Português

### Sobre

Aplicação de terminal que gerencia a operação de uma distribuidora. Funcionários
cadastram pedidos, e o sistema controla as entregas e os entregadores
responsáveis por realizá-las. O modelo relacional foi projetado no MySQL
Workbench, e a camada de aplicação — em Python — se conecta ao banco para
executar todas as operações. As entregas são o foco do projeto.

### Funcionalidades

- Cadastro e gerenciamento de pedidos feitos pelos funcionários
- Controle de entregas e dos entregadores associados a cada uma
- Modelo de dados relacional com relacionamentos entre funcionários, pedidos, entregas e entregadores
- Resultados exibidos como tabelas formatadas no terminal

### Tecnologias

**Python** · **MySQL** · `mysql-connector-python` · `tabulate`

### Modelo de Dados

O banco é modelado em `sqldistribuidora.mwb` (MySQL Workbench) e criado a partir
de `Distribuidora_TrabF.sql`. Uma visão geral do schema está em `foto.png`.

### Como Executar

**Pré-requisitos:** Python 3.x e um MySQL Server ativo.

```bash
# 1. Clone o repositório
git clone https://github.com/Myrodian/Trab_Distribuidora.git
cd Trab_Distribuidora

# 2. Crie o banco (rode o script SQL no MySQL)
mysql -u root -p < Distribuidora_TrabF.sql

# 3. Instale as dependências
pip install mysql-connector-python tabulate

# 4. Rode a aplicação
python distribuidora/main.py
```

> Antes de rodar, atualize os dados de conexão (host, usuário, senha) no código
> para corresponder à sua instalação local do MySQL.

### O que pratiquei

Modelagem de banco relacional, SQL (DDL/DML), conexão de uma aplicação a um banco
de dados e operações CRUD sobre tabelas relacionadas.

---

**Author / Autor:** Augusto Leal · [LinkedIn](https://www.linkedin.com/in/augusto-leal11/)
