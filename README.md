
# Tasks-Web

Tasks-Web é um projeto web desenvolvido com React, TypeScript e Vite. Ele utiliza várias bibliotecas modernas para construção de UI, gerenciamento de formulários, roteamento e validação. O projeto está configurado para desenvolvimento rápido com hot-reloading e possui scripts para construção, linting e pré-visualização.

## Índice
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Executando a Aplicação](#executando-a-aplicação)
- [Executando a Aplicação com Docker](#executando-a-aplicação-com-docker)
- [Executando Testes](#executando-testes)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Licença](#licença)

## Pré-requisitos

Certifique-se de ter o seguinte instalado:

- [Node.js](https://nodejs.org/) (se executar sem Docker)


## Instalação

1. Clone o repositório:

   ```sh
   git clone git@github.com:fernandomeddev/taskweb.git
   

## Executando a Aplicação
1. Instale as dependências:

   ```sh
   npm install

2. Construa o projeto:

   ```sh
   npm run dev

O servidor estará em execução em http://localhost:5173.


## Estrutura do Projeto
   ```sh
   tasks-web/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   ├── utils/
│   ├── App.tsx
│   ├── main.tsx
│   ├── vite-env.d.ts
├── public/
│   ├── index.html
├── dist/
├── package.json
├── tailwind.config.js
├── tsconfig.json
├── vite.config.ts
└── README.md


## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
