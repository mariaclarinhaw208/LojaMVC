# 🛒 LojaMVC

Sistema desenvolvido em **ASP.NET Core MVC**, utilizando a linguagem **C#** e o padrão arquitetural **Model-View-Controller (MVC)**.

O projeto tem como objetivo demonstrar a implementação de um sistema CRUD (Create, Read, Update e Delete) para gerenciamento de **Clientes e Produtos**, utilizando o **Entity Framework Core** para persistência de dados e uma interface web responsiva.

---

## 📋 Tecnologias Utilizadas

- C#
- .NET
- ASP.NET Core MVC
- SQL Server
- Entity Framework Core
- Bootstrap
- Razor Views
- HTML5
- CSS3
- JavaScript
- jQuery

---

## 📦 Pacotes Utilizados

O projeto utiliza pacotes do Entity Framework Core para gerenciamento e persistência dos dados.

Principais pacotes:

- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.SqlServer
- Microsoft.EntityFrameworkCore.Tools
- Microsoft.EntityFrameworkCore.Design
- Microsoft.VisualStudio.Web.CodeGeneration.Design

---

## 🗄 Banco de Dados

O banco de dados utilizado pelo sistema é o **SQL Server**.

A estrutura do banco é criada utilizando a abordagem **Code First**, através do **Entity Framework Core** e suas respectivas **Migrations**.

As entidades do sistema são utilizadas para representar os dados de clientes e produtos, permitindo realizar operações de cadastro, consulta, alteração e exclusão.

---

## 🚀 Funcionalidades

O sistema possui as seguintes funcionalidades:

### 👤 Clientes

- Cadastro de clientes
- Consulta de clientes
- Alteração de clientes
- Exclusão de clientes
- Visualização dos detalhes dos clientes
- Controle de informações como nome, e-mail, idade e status de ativo

### 📦 Produtos

- Cadastro de produtos
- Consulta de produtos
- Alteração de produtos
- Exclusão de produtos
- Visualização dos produtos
- Controle de preço
- Controle de estoque

### 🌐 Sistema

- Página inicial
- Menu de navegação
- Página de privacidade
- Gerenciamento de clientes
- Gerenciamento de produtos
- Interface responsiva
- Operações CRUD utilizando ASP.NET Core MVC

---

## 🎨 Interface

A interface do sistema foi desenvolvida utilizando **Razor Views**, **Bootstrap**, HTML e CSS.

O sistema possui uma interface simples e organizada, com:

- Menu de navegação
- Página inicial
- Tabelas para apresentação dos registros
- Botões para criação e gerenciamento dos dados
- Formulários para cadastro e edição
- Páginas de detalhes
- Layout responsivo

---

## 🧭 Navegação

O sistema possui um menu principal com acesso às seguintes áreas:

- **Início**
- **Privacidade**
- **Cliente**
- **Produto**

A opção **Cliente** direciona para o gerenciamento dos clientes cadastrados.

A opção **Produto** direciona para o gerenciamento dos produtos cadastrados.

---

## 👤 Gerenciamento de Clientes

A área de clientes apresenta os registros cadastrados em formato de tabela.

São exibidas informações como:

- Nome
- E-mail
- Idade
- Status de ativo

Para cada registro existem opções para:

- **Edit** — alterar o cadastro
- **Details** — visualizar os detalhes
- **Delete** — excluir o registro

Também existe a opção **Create New**, utilizada para cadastrar um novo cliente.

---

## 📦 Gerenciamento de Produtos

A área de produtos permite realizar o gerenciamento dos produtos cadastrados.

A listagem apresenta informações como:

- Nome
- Preço
- Estoque

Assim como no gerenciamento de clientes, é possível realizar operações de cadastro, consulta, alteração e exclusão dos registros.

---

# ▶️ Como Executar o Projeto

## 1. Clone o repositório

```bash
git clone https://github.com/mariaclarinhaw208/AcademiaCrud3.git
