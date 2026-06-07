<p align="center">
  <img src="https://img.icons8.com/external-flatart-icons-flat-flatarticons/128/000000/external-ticket-entertainment-flatart-icons-flat-flatarticons.png" width="100" alt="StockOS Logo" />
</p>

<h1 align="center">StockOS - Gerenciamento de Estoque</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p align="center">
  <b>Uma plataforma de gerenciamento de estoque altamente escalável, construída com Clean Architecture e DDD.</b>
</p>

---

## 📖 Conteúdo
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Arquitetura do Sistema](#-arquitetura-do-sistema)
- [Stack Tecnológica](#-stack-tecnológica)
- [Como Começar](#-como-começar)

---

## 🌟 Sobre o Projeto
StockOS é uma solução moderna para gerenciamento de estoque. O sistema foi desenhado para ser modular, seguindo princípios de Clean Architecture para garantir facilidade de manutenção e evolução.

---

## ✨ Funcionalidades Principais

- 🔐 **Autenticação Segura:** Login e registro com JWT e hash de senhas via Argon2.
- 📦 **Gestão de Produtos:** CRUD completo de produtos protegido por autenticação.
- 🏗️ **Arquitetura Limpa:** Separação clara entre domínio, aplicação e infraestrutura.

---

## 🏗️ Arquitetura do Sistema

### 💎 Clean Architecture
A lógica de negócio (Entidades e Casos de Uso) é isolada de ferramentas externas, tornando o sistema independente de frameworks.

### 🧩 Domain-Driven Design (DDD)
- **Entidades Ricas:** Regras de negócio encapsuladas nos modelos de domínio.
- **Repository Pattern:** Abstração da camada de persistência.
- **DTOs:** Contratos de dados claros entre as camadas.

---

## 🛠️ Stack Tecnológica

| Categoria | Tecnologia |
| :--- | :--- |
| **Linguagem** | JavaScript (Node.js) |
| **Banco de Dados** | MySQL |
| **ORM** | Sequelize |
| **Segurança** | Argon2, JWT |
| **DevOps** | Docker |

---

## 🚦 Como Começar

### Pré-requisitos
- Docker & Docker Compose
- Node.js 18+

### Início Rápido
```bash
git clone <url-do-seu-repositorio>
cd projeto/backend
# Configure o arquivo .env com base no .env.example
docker-compose up --build
```

---

<p align="center">
  Feito com ❤️ para a Comunidade de Desenvolvedores.
</p>
