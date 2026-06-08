<p align="center">
  <img src="https://img.icons8.com/external-flatart-icons-flat-flatarticons/128/000000/external-box-delivery-flatart-icons-flat-flatarticons.png" width="100" alt="StockOS Logo" />
</p>

<h1 align="center">StockOS - Enterprise Inventory System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
</p>

<p align="center">
  <b>A robust, full-stack inventory management solution built with Clean Architecture, DDD, and professional security standards.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/marceloferreiracampos07/Projeto-Estoque---Desenvolvimento-Desktop?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture-Clean_Arch-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Security-JWT_%26_Argon2-green?style=flat-square" />
</p>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [SOLID Principles](#-solid-principles-applied)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Summary](#-project-summary-latest-updates)

---

## 🌟 About the Project
StockOS is an enterprise-grade solution for inventory control. It bridges the gap between complex industrial requirements and a seamless user experience, ensuring that inventory tracking, user management, and financial reporting are handled with precision and security.

---

## ✨ Key Features

- 🔐 **Secure Authentication:** Identity management using **Argon2** hashing and **JWT** stateless sessions.
- 📊 **Dynamic Dashboard:** Real-time calculation of total assets, SKU count, and critical stock alerts.
- 📦 **Inventory Lifecycle:** Complete CRUD operations for products with category-based filtering.
- 🚀 **Performance Optimized:** Asynchronous communication and optimized SQL queries via Sequelize.
- 🎨 **Premium UI/UX:** A modern, dark-themed interface built for speed and visual clarity.

---

## 🏗️ System Architecture

### 💎 Clean Architecture
The backend is structured to decouple business rules from external technologies.
- **Entities & Use Cases:** Core logic remains pure and independent.
- **Infrastructure Layer:** Handles database persistence (Sequelize), HTTP (Express), and configurations.

### 🧩 Domain-Driven Design (DDD)
- **Ubiquitous Language:** Code reflects business terms (Product, Inventory, StockAlert).
- **Repository Pattern:** Abstracted data access layers for scalability and testability.
- **DTOs:** Strict data transfer objects using **Zod** for schema validation.

---

## 🛡️ SOLID Principles Applied

StockOS is built on a foundation of maintainable software design:

- **S - SRP:** Controllers only handle HTTP requests; Use Cases only handle business logic.
- **O - OCP:** New features (like new repository types) can be added without modifying existing business rules.
- **L - LSP:** Repository implementations can be swapped without breaking the service layer.
- **I - ISP:** Interfaces are lean and focused on specific domain needs.
- **D - DIP:** High-level modules depend on abstractions, ensuring the core logic is never coupled to a specific DB or framework.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Backend** | Node.js, Express |
| **Database** | MySQL, Sequelize ORM |
| **Security** | Argon2, JWT, Zod |
| **Frontend** | Vanilla JS (ES6+), CSS3 Modern |
| **Deployment** | Vercel (Frontend), Render (Backend) |

---

## 🚦 Getting Started

### Prerequisites
- Node.js 18+
- MySQL Database

### Quick Start
```bash
# Clone the repository
git clone https://github.com/marceloferreiracampos07/Projeto-Estoque---Desenvolvimento-Desktop.git

# Setup Backend
cd src/backend
npm install
# Configure .env based on .env.example
npm run dev

# Setup Frontend
# Just open src/renderer/views/index.html or serve it locally
```

---

## 📋 Project Summary (Latest Updates)
<details>
<summary>Click to view latest development report</summary>

### 📊 Relatório de Atividades - StockOS

#### 1. Segurança & Infraestrutura
- Implementação de variáveis de ambiente para JWT e Banco de Dados.
- Configuração de CORS para suporte a desenvolvimento local e produção.
- Proteção de arquivos sensíveis via `.gitignore`.

#### 2. Refatoração Clean Code (Finalizado)
- Padronização de nomenclatura para English camelCase.
- Remoção de comentários redundantes e "noise".
- Modularização do `apiClient` e lógica de autenticação.

#### 3. UX & Fixes (Finalizado)
- Correção do loop de redirecionamento no login.
- Sincronização em tempo real do Dashboard com a API.
- Validação de segurança em tempo real no cadastro de usuários.

#### 🚀 Status Final
| Módulo | Qualidade | Status |
| :--- | :--- | :--- |
| **Backend API** | Senior Refactored | 🟢 Production Ready |
| **Frontend UI** | Clean & Modern | 🟢 Production Ready |
</details>

---
<p align="center">
  Made with ❤️ for the Developer Community.
</p>
