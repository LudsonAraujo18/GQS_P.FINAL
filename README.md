# Sistema de Controle de Vendas e Clientes

## Projeto Final - Gestão da Qualidade de Software (GQS)

---

## Descrição do Projeto

Este projeto é uma aplicação web para gerenciamento de vendas e clientes, desenvolvida com arquitetura MVC. O sistema permite o cadastro, edição, visualização e exclusão de clientes e vendas. A aplicação foi construída com foco na qualidade de software, incluindo testes unitários, de integração e end-to-end (E2E).

### Estrutura do Projeto

```
projeto-final/
├── src/
│   ├── controllers/          # Controladores (lógica de negócio)
│   ├── models/              # Modelos (acesso a dados)
│   ├── routes/              # Rotas da aplicação
│   ├── views/               # Views (interface do usuário)
│   ├── public/              # Arquivos estáticos
│   └── database/            # Configuração do banco
├── tests/                   # Testes automatizados
│   ├── unit/               # Testes unitários
│   └── integration/        # Testes de integração
├── cypress/                # Testes E2E
├── app.js                  # Arquivo principal
├── package.json            # Dependências e scripts
├── cypress.config.js       # Configuração do Cypress
└── README.md              # Documentação
```

## Instalação e Configuração

### Pré-requisitos

- Node.js (versão 18 ou superior)

- npm (gerenciador de pacotes do Node.js)

### Passos para Instalação

1. **Clone ou baixe o projeto:**

1. **Instale as dependências:**

1. **Inicie a aplicação:**

1. **Acesse a aplicação:**
  - Abra seu navegador e acesse: `http://localhost:3000`

### Scripts Disponíveis

- `npm start` - Inicia a aplicação

- `npm test` - Executa todos os testes

- `npm run test:unit` - Executa testes unitários

- `npm run test:integration` - Executa testes de integração

- `npm run test:e2e` - Executa testes E2E com Cypress

- `npm run cypress:open` - Abre a interface gráfica do Cypress
