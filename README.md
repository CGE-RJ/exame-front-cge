# Exame Front CGE

Este é o repositório do projeto Exame Front CGE, um teste de desenvolvimento web. O projeto consiste em duas partes: o frontend, desenvolvido em Next.js com TypeScript, e o backend, desenvolvido em Node.js com MongoDB. O objetivo é criar uma aplicação de gerenciamento de categorias de produtos e produtos, com operações CRUD (Create, Read, Update, Delete).

## Requisitos

Certifique-se de atender aos seguintes requisitos antes de iniciar o teste:

- Node.js na versão 18.16.1 instalado. Recomendamos o uso do NVM (Node Version Manager) para gerenciar as versões do Node.js.

```bash
nvm install 18.16.1
nvm use 18.16.1
```

## Configuração do Frontend

Para configurar o ambiente de desenvolvimento do frontend, siga estas etapas:

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

Para configurar o ambiente de desenvolvimento do backend, siga estas etapas:

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

## Detalhes do Teste

Este teste consiste em desenvolver um aplicativo de gerenciamento de categorias de produtos e produtos com as seguintes funcionalidades:

**Backend**:
- Crie uma API RESTful em Node.js usando o Express para gerenciar as categorias de produtos e produtos.
- Utilize o MongoDB como banco de dados para armazenar as informações das categorias e produtos.
- Implemente operações CRUD para categorias e produtos (Create, Read, Update, Delete).
- Mantenha um código limpo e bem documentado.
- Implemente um sistema de registro e login como bônus.

**Frontend**:
- Crie uma aplicação React com Next.js para interagir com a API do backend.
- Implemente páginas para listar categorias e produtos, bem como para adicionar, editar e excluir categorias e produtos.
- Garanta uma interface amigável e responsiva.
- Integre a aplicação frontend com a API backend para realizar operações CRUD.
- Utilize um sistema de rotas apropriado no Next.js.

**Integração**:
- As operações CRUD no frontend devem estar conectadas às rotas da API RESTful no backend.
- Use métodos HTTP apropriados (GET, POST, PUT, DELETE) para interagir com os recursos do servidor.

## Critérios de Avaliação

Sua prova será avaliada com base nos seguintes critérios:

- Funcionalidade completa: Todas as operações CRUD (Create, Read, Update, Delete) para categorias e produtos devem funcionar corretamente.
- Qualidade do código: O código deve ser organizado, seguir as melhores práticas e estar bem documentado.
- Integração frontend/backend: A integração entre o frontend e o backend deve ser eficaz e segura.
- Interface de usuário: A interface deve ser amigável.
- Bônus (sistema de registro/login): Se você implementar essa funcionalidade, ela será considerada um bônus.

## Entrega

Após concluir o teste, envie seu código para revisão. Certifique-se de incluir todas as funcionalidades e seguir as melhores práticas de desenvolvimento. Boa sorte!