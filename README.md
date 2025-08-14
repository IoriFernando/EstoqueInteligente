# 📦 EstoqueInteligente

*EstoqueInteligente* é uma solução moderna para gerenciamento inteligente de estoque em depósitos, desenvolvida para otimizar organização, rastreamento e controle de produtos.
Com recursos intuitivos, o sistema permite cadastrar, atualizar e monitorar itens em tempo real, reduzindo perdas e aumentando a produtividade.

## ✨ Funcionalidades Principais

### ✅ Cadastro de Produtos
    Nome, código, quantidade, categoria e localização.

### 📥 Controle de Entrada e Saída 
    Registro de movimentações com atualização automática do estoque.

### 📊 Relatórios e Análises 
     Inventário, sazonalidade e produtos críticos.

### 🔔 Alertas de Reposição 
    Notificações para níveis mínimos de estoque.

### 🖥 Interface Intuitiva 
    Dashboard amigável, busca rápida e filtros avançados.

## 🛠️ Tecnologias Utilizadas

### Backend

- Java

- Spring Boot (Spring Web, Spring Data JPA, Spring Security, Spring Boot DevTools, MySQL Driver)

### Frontend

- React

- Vue.js

- HTML5, CSS3

### Banco de Dados

- MySQL

### Ferramentas & Controle de Versão

- Git

- GitHub

## 🎯 Objetivo

Automatizar e simplificar a gestão de estoque em depósitos, garantindo precisão nos dados e agilidade nas operações diárias.

## 📌 Casos de Uso

- 🚚 Empresas de logística

- 🏭 Centros de distribuição

- 🏪 Comércios atacadistas

- 📦 Pequenos e médios depósitos

- 🚚 Empresas de logística

- 🏭 Centros de distribuição

- 🏪 Comércios atacadistas

- 📦 Pequenos e médios depósitos


## 📂 Estrutura do Projeto
```bash
EstoqueInteligente/
│
├── backend/                  # API REST com Java + Spring Boot
│   ├── src/main/java/com/exemplo/deposito
│   │   ├── controller        # Endpoints da aplicação
│   │   ├── model             # Entidades JPA
│   │   ├── repository        # Interfaces de persistência
│   │   ├── service           # Regras de negócio
│   │   └── Application.java  # Classe principal
│   └── pom.xml
│
├── frontend/                 # Interface Web
│   ├── src/
│   │   ├── components        # Componentes reutilizáveis
│   │   ├── pages             # Páginas do sistema
│   │   ├── services          # Integração com a API
│   │   └── App.js
│   ├── package.json
│
└── README.md
```