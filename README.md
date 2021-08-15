<h1 align="center">
  <img src=".github/logo.svg" alt="My Money">
</h1>

<h3 align="center">
  My Money - O acompanhamento da sua carteira.
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/kleytonsolinho/thebehero">
  
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/kleytonsolinho/thebehero">
  
  <a href="https://www.codacy.com/manual/kleytonsolinho/thebehero?    utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kleytonsolinho/thebehero&amp;utm_campaign=Badge_Grade">
  <img src="https://api.codacy.com/project/badge/Grade/af7ef38b79414492844663ebbbf4e21b"/>
  </a>
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/kleytonsolinho/thebehero">
  
  <a href="https://github.com/kleytonsolinho/thebehero/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/kleytonsolinho/thebehero">
  </a>
  
  <a href="https://github.com/kleytonsolinho/thebehero/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/kleytonsolinho/thebehero">
  </a>
  
  <img alt="GitHub" src="https://img.shields.io/github/license/kleytonsolinho/thebehero">
</p>

<p align="center">
  <a href="#%EF%B8%8F-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalação-execução-e-desenvolvimento">Instalação, execução e desenvolvimento</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p id="insomniaButton" align="center">
  <a href="https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Tobehero%20API&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fengividal%2Ftobehero%2Fmaster%2Finsomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

<img alt="Layout" src=".github/tobehero.png" />

## 📋 Projeto

Aplicação completa utilizando a Stack do Javascript. O objetivo da aplicação é permitir que ONGs possam cadastrar casos a serem visualizados pelo possíveis voluntários que queiram colaborar. 

O Frontend Web permite o cadastro de novas ONGs e novos Casos. Os casos possuem detalhes para auxiliar quem tiver interesse em ajudar e entrar em contato com as ONGs.

O aplicativo é voltado para o usuário final, possível voluntário, que poderá visualizar todos os casos disponíveis e entrar em contato com a organização que criou o caso via e-mail ou whatsapp.  

## 🔝 Tecnologias

Esta aplicação foi desenolvida com as tecnologias abaixo:

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [Celebrate](https://github.com/arb/celebrate)
- [SQLite](https://www.sqlite.org/)
- [Jest](https://jestjs.io/)
- [SuperTest](https://github.com/visionmedia/supertest)
- [Nodemon](https://nodemon.io/)
- [React Navigation](https://reactnavigation.org/)
- [React Icons](https://react-icons.netlify.com/#/)
- [Axios](https://github.com/axios/axios)

## 💻 Instalação e execução

Faça um clone do repositório através do [GitHub Desktop](https://desktop.github.com/) ou linha de comando `git clone https://github.com/kleytonsolinho/thebehero.git`.

### Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [SQLite](https://www.sqlite.org/)
- [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/)
- [Expo](https://expo.io/)

### Backend

- A partir da raiz do projeto, entre na pasta rodando `cd backend`;
- Rode `yarn` para instalar sua dependências;
- Importe o arquivo `Insomnia.json` no Insomnia ou clique no botão [Run in Insomnia](#insomniaButton);

### Web

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd web`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` para iniciar o client web;

### Mobile

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd mobile`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` ou `expo start` para iniciar o bundle com o expo;
- Caso vá utilizar seu smartphone, com o app do expo escaneia o QRCODE;

## ❤️ Como contribuir

**Faça um fork deste repositório**

<!-- - Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`; -->

```bash
# Clone o seu fork
$ git clone url-do-seu-fork && cd tobehero

# Crie uma branch com sua feature
$ git checkout -b minha-feature

# Faça o commit das suas alterações
$ git commit -m 'feat: Minha nova feature'

# Faça o push para a sua branch
$ git push origin minha-feature
```

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/kleytonsolinho/thebehero/blob/master/LICENSE) para mais detalhes.

---

## 🙏 Agradecimentos 

- CTO Rocketseat [Diego Fernandes](https://github.com/diego3g)
- Rocketseat pela semana de Aprendizagem [Rocketseat](https://github.com/rocketseat)
