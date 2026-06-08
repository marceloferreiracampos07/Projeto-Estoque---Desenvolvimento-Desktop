# StockOS - Gestão de Estoque Enterprise

StockOS é uma solução robusta e moderna para gerenciamento de inventário, desenvolvida com uma arquitetura de alta performance, foco em segurança e experiência do usuário excepcional.

## 🚀 Funcionalidades

- **Dashboard em Tempo Real:** Monitoramento dinâmico de patrimônio, total de itens e alertas de estoque baixo.
- **Gestão de Inventário Full-Stack:** Operações CRUD completas integradas a um backend persistente.
- **Segurança Avançada:** 
    - Autenticação via JWT (JSON Web Tokens).
    - Criptografia de senhas com Argon2.
    - Validação de dados rigorosa com Zod (Backend) e Regex (Frontend).
- **Interface Premium:** Design moderno com foco em usabilidade, feedback visual imediato e responsividade.
- **Arquitetura Limpa:** Organizado seguindo princípios de Clean Architecture e DDD (Domain-Driven Design).

## 🛠️ Tecnologias Utilizadas

### Backend
- **Node.js & Express:** Servidor de alta performance.
- **Sequelize ORM:** Gestão de banco de dados SQL (MySQL/PostgreSQL).
- **Argon2:** Criptografia de senhas de última geração.
- **JSON Web Token (JWT):** Segurança e controle de sessão.
- **Zod:** Validação de esquemas e tipos de dados.

### Frontend
- **Vanilla JavaScript (ES6+):** Lógica modular e assíncrona.
- **Fetch API:** Comunicação com o backend.
- **CSS3 Moderno:** Custom properties, Flexbox e Grid para uma interface fluida.
- **Vercel:** Hospedagem e deploy otimizado.

## 📁 Estrutura do Projeto

O projeto é dividido em duas camadas principais:

```text
projeto/
└── src/
    ├── backend/          # API REST com Clean Architecture
    │   ├── application/  # Casos de uso e DTOs
    │   ├── domain/       # Entidades e interfaces de repositório
    │   └── infrastructure/# Implementações técnicas (DB, HTTP, Config)
    └── renderer/         # Frontend da aplicação
        ├── css/          # Estilização modular
        ├── js/           # Lógica do cliente e apiClient
        └── views/        # Estrutura HTML
```

## ⚙️ Instalação e Configuração

### Pré-requisitos
- Node.js (v18+)
- Banco de Dados SQL (MySQL recomendado)

### Configuração do Backend
1. Navegue até `src/backend`.
2. Copie o arquivo `.env.example` para `.env`.
3. Preencha as credenciais do seu banco de dados e defina um `JWT_SECRET`.
4. Instale as dependências e inicie:
   ```bash
   npm install
   npm run dev
   ```

### Configuração do Frontend
1. Navegue até `src/renderer`.
2. Os scripts utilizam o `apiClient.js` que detecta automaticamente se a API está rodando localmente ou em produção.
3. Se estiver em desenvolvimento, certifique-se de que o backend está rodando na porta 3000.

## 🛡️ Segurança e Boas Práticas
- Variáveis de ambiente protegidas e ignoradas pelo controle de versão.
- Proteção contra CORS configurada para domínios específicos.
- Tratamento global de erros e validações de input tanto no cliente quanto no servidor.

## 📄 Licença
Este projeto está sob a licença ISC.
