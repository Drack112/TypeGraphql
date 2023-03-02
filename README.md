<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-rodando">Rodando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<a id="rocket-tecnologias"></a>

## 🚀 Tecnologias

<div align="center">
 	   <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
     <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
     <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
     <img src="https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql" />
     <img src="https://img.shields.io/badge/-TypeGraphQL-%23C04392?style=for-the-badge" />

</div>

<br>
<a id="-projeto"></a>

## 💻 Projeto

Um teste simples sobre o Framework **_[TypeGraphql](https://typegraphql.com/)_**. Sua função é combinar o TypeScript com GraphQL de uma forma ez.

<a id="-layout"></a>

<a id="-rodando"></a>

## Rodando o projeto 🌇

## Requerimentos:

- [NodeJS](https://nodejs.org/en/)
- [Docker](https://www.docker.com/)

## 📂 Instalando as dependências:

Yarn:

```bash
yarn install
```

NPM:

```bash
npm install
```

### 🐬 Iniciando o Banco de dados:

Preencha as informações do arquivo `.env.example` e renomeie para `.env`

```env
MONGO_DB=
MONGO_USER=
MONGO_PASSWORD=
```

Subir banco de dados MongoDB:

```bash
docker-compose up db
```

## 🚀 Executando a aplicação:

Apenas de o comando:

```bash
yarn dev
#ou
npm run dev
```

<a id="-como-contribuir"></a>

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.
