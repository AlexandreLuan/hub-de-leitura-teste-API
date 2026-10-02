# 🚀 Testes de API com Cypress

Projeto desenvolvido para estudos de automação de testes de API utilizando Cypress.

---

## 🎯 Objetivo

Validar os principais fluxos da API de Gestão de Usuários através de testes automatizados, garantindo a qualidade das regras de negócio e das respostas da aplicação.

---

## 🛠️ Tecnologias Utilizadas

- ✅ Cypress
- ✅ JavaScript
- ✅ Node.js
- ✅ REST API
- ✅ GitHub

---

## 📚 Funcionalidades Testadas

### 🔍 GET

- Listar usuários
- Buscar usuário por ID
- Buscar usuário com filtros

### ➕ POST

- Cadastrar usuário com sucesso
- Validar cadastro com e-mail inválido

### ✏️ PUT

- Atualizar usuário existente
- Atualizar usuário criado dinamicamente

### 🗑️ DELETE

- Excluir usuário existente
- Excluir usuário criado dinamicamente

---

## ✅ Validações Implementadas

- Status Code HTTP
- Mensagens de sucesso
- Mensagens de erro
- Estrutura da resposta
- Regras de negócio
- Autenticação via Token

---

## 📂 Estrutura do Projeto

```text
📦 projeto
├── 📁 cypress
│   ├── 📁 e2e
│   ├── 📁 support
│   └── 📁 fixtures
├── 📄 cypress.config.js
├── 📄 package.json
└── 📄 README.md
```

---

## ▶️ Como Executar

### Instalar dependências

```bash
npm install
```

### Abrir o Cypress

```bash
npx cypress open
```

### Executar todos os testes

```bash
npx cypress run
```

---

## 🎓 Aprendizados

Durante este projeto foram praticados conceitos como:

🧪 Testes de API

🔐 Autenticação por Token

📦 Commands Customizados

⚡ Assertions

🔄 Métodos HTTP (GET, POST, PUT e DELETE)

🚀 Automação com Cypress

📊 Boas práticas de QA

---

## 👨‍💻 Autor

**Alexandre Luan**

🔗 GitHub: https://github.com/AlexandreLuan

💼 LinkedIn: (https://www.linkedin.com/in/alexandre-luan-dos-santos-9a5685288/)

---

⭐ Projeto desenvolvido para fins de estudo e aprimoramento em Qualidade de Software e Automação de Testes.
