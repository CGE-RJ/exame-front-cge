# Exame Front CGE

Este é o repositório do projeto Exame Front CGE. O projeto possui uma parte de frontend (desenvolvido em Next.js com TypeScript) e uma parte de backend (Node.js com MongoDB) para realizar operações CRUD.

## Requisitos

Certifique-se de ter o Node.js na versão 18.16.1 instalado. Recomendamos o uso do NVM (Node Version Manager) para gerenciar as versões do Node.js.

```bash
nvm install 18.16.1
nvm use 18.16.1
```

## Configuração do Frontend

1. Navegue até a pasta do frontend:

```bash
cd front
```

2. Instale as dependências do projeto:

```bash
yarn install
```

3. Após a instalação das dependências, construa o projeto e inicie o servidor de desenvolvimento:

```bash
yarn build
yarn dev
```

Seu projeto frontend estará pronto em http://localhost:3000.

## Configuração do Backend

1. Volte para a raiz do projeto:

```bash
cd ..
```

2. Navegue até a pasta do backend:

```bash
cd back
```

3. Crie os arquivos necessários para rodar um servidor Node.js para realizar as ações de CRUD com MongoDB. Você precisará criar rotas, controladores e configurar a conexão com o banco de dados de acordo com os requisitos do seu projeto.

Com esses passos, você terá configurado e iniciado o frontend e terá acesso ao backend para desenvolver seu projeto Exame Front CGE. Lembre-se de configurar corretamente as rotas e as chamadas de API entre o frontend e o backend de acordo com as necessidades do seu projeto.