<h1 align="center">
    <img alt="Proffy" src=".github/logo.svg" height="100px" />
    <br>Next Level Week <br/>
    Node.js | ReactJS
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/PauloEwerson/Proffy?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/PauloEwerson/Proffy?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/PauloEwerson/Proffy?style=flat-square"> 
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
</p>

<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="mockup do projeto" width="650px" src="./.github/mockup.png" />
<p>

## :bookmark: Sobre

O **Proffy** é uma aplicação Web desenvolvida para auxiliar a conexão entre os alunos e professores, possibilitando registrar aulas, adicionar informações como a disciplina, custo e horário das aulas, bem como a possibilidade de buscar pelas aulas cadastradas.

Este projeto foi desenvolvido com inspiração na data **6 de agosto**, onde se comemora o **Dia Nacional dos Profissionais da Educação**.

Essa aplicação foi realizada durante a Next **Level Week #2**, projeto da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [Express](https://expressjs.com/)
-  [Axios](https://github.com/axios/axios)

## :boom: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  
1. Clonando o repositório:

```sh
  $ git clone https://github.com/PauloEwerson/Proffy.git
```

2.Executando a aplicação:

```sh
  # API
  $ cd server
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Configurando o banco de dados e criando as tabelas.
  $ yarn knex:migrate # ou npm run knex:migrate

  # Inicie a API
  $ yarn start # ou npm start

  # Aplicação web
  $ cd web
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), CTO [Rocketseat](rocketseat.com.br).</sup>
