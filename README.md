# CRUD em Node.js

Back-end de uma aplicação **CRUD básica** desenvolvido com **Node.js** e **NeonDB (PostgreSQL)**.  
O projeto tem como foco a implementação de uma **API REST simples**, aplicando conceitos fundamentais de desenvolvimento back-end.

## 🎯 Objetivo do projeto

Construir uma API organizada e funcional para realizar operações básicas de **Create, Read, Update e Delete (CRUD)**, consolidando os fundamentos de back-end, como:

- Arquitetura REST
- Persistência de dados em banco relacional
- Organização e estruturação de código
- Comunicação via API HTTP

## ⚙️ Funcionalidades

- Criação de registros
- Listagem de registros
- Atualização de registros
- Remoção de registros
- Comunicação via API REST

## 🛠️ Tecnologias e ferramentas

- **Node.js**
- **Express**
- **NeonDB (PostgreSQL)**
- **dotenv**

## 📋 Pré-requisitos

Para executar o projeto localmente, é necessário ter instalado:

- **Node.js**
- Conta no **NeonDB** ou outro banco de dados PostgreSQL compatível

---

## ▶️ Execução do projeto

### 1. Clone o repositório
```bash
git clone https://github.com/Amannu1/node-crud
2. Acesse o diretório do projeto
cd node-crud
3. Instale as dependências
npm install
4. Configure as variáveis de ambiente
Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

DATABASE_URL="postgresql://usuario:senha@host/database"
DATABASE_URL: string de conexão com o banco de dados PostgreSQL (NeonDB)

5. Inicie a aplicação
npm start
A API será iniciada e ficará disponível para requisições HTTP.

🧠 Principais aprendizados
Desenvolvimento de APIs REST com Node.js e Express

Integração com banco de dados relacional (PostgreSQL)

Implementação de operações CRUD

Organização básica de projetos back-end

Uso de variáveis de ambiente para configuração segura

📌 Observações
Este projeto possui finalidade educacional e foi desenvolvido para prática dos fundamentos de desenvolvimento back-end.
