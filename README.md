# EstoqueInteligente
O EstoqueInteligente é uma solução eficiente para gerenciamento de estoque em depósitos, desenvolvido para otimizar a organização, rastreamento e controle de produtos. Com recursos intuitivos, o sistema permite cadastrar, atualizar e monitorar itens em tempo real, reduzindo perdas e melhorando a produtividade.

✨ Principais Funcionalidades:
✔ Cadastro de Produtos – Adicione itens com nome, código, quantidade, categoria e localização.
✔ Controle de Entrada e Saída – Registre movimentações e atualize automaticamente o estoque.
✔ Relatórios e Análises – Gere relatórios de inventário, sazonalidade e produtos críticos.
✔ Alertas de Reposição – Notificações quando os itens atingirem o nível mínimo.
✔ Interface Intuitiva – Dashboard fácil de usar, com busca rápida e filtros avançados.

🛠️ Tecnologias Utilizadas:

    Backend: Java, Spring Boot (Dependências: Spring Web, Spring Data JPA, MySQL Driver, Spring Boot DevTools, Spring Security)

    Frontend: React, Vue.js, HTML/CSS

    Banco de Dados: MySQL

    Ferramentas: Git,GitHub

🎯 Objetivo:
Automatizar e simplificar a gestão de estoque em depósitos, garantindo precisão nos dados e agilidade nas operações diárias.

📌 Casos de Uso:

    Empresas de logística

    Centros de distribuição

    Comércios atacadistas

    Pequenos e médios depósitos

📂 Estrutura do Projeto:

EstoqueInteligente / Estrutura do projeto
│
├── backend/ (Java + Spring Boot)
│   ├── src/main/java/com/exemplo/deposito
│   │   ├── controller
│   │   ├── model
│   │   ├── repository
│   │   ├── service
│   │   └── Application.java
│   └── pom.xml
│
├── frontend/ (React)
│   ├── src/
│   │   ├── components
│   │   ├── pages
│   │   ├── services (para chamadas à API)
│   │   └── App.js
│   ├── package.json
│
└── README.md

📦 Instalação das Dependências

Para utilizar este projeto, instale as dependências necessárias executando o seguinte comando:


npm install axios react-router-dom