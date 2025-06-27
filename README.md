**Read in another language: [Українська](README.ukr.md), [English](README.md).**

# Job Board typescript client

---

[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](#)
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](#)
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](#)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](#)
[![GraphQL](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![ApolloGraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)](#)
[![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](#)

This is the React/GraphQL/Apollo client from the [Job Board client](https://github.com/labattaria/job-board-client) repo, but migrated and converted to TypeScript

The client-side application was slightly refactored using TypeScript, which added type safety to the code

It uses the GraphQL TypeScript code generator, which allows us to generate TypeScript types and gql-graphql functions from our GraphQL schema, queries, and mutations

This client app is only part of the application, the second part (the server) is located at this repo: [Job Board typescript server](https://github.com/labattaria/job-board-server-ts)

The app in this repo works with the server hosted at [https://render.com](https://render.com), hosting public URL: [https://job-board-server-ts.onrender.com/graphql](https://job-board-server-ts.onrender.com/graphql)

## Used dependencies:

- **TypeScript** - Language that builds on JavaScript by adding static types, helping developers catch errors early and write more reliable code
- **GraphQL Code Generator** - Tool that automatically generates TypeScript types (or other language types) and boilerplate code based on your GraphQL schema and operations
- **Vite** - A fast and modern build tool that provides lightning-fast hot module replacement (HMR) for development, optimized for frameworks
- **React** - Library used for building user interfaces, particularly for single-page applications where you need a fast, interactive experience
- **GraphQL** - Core GraphQL library
- **JWT (JSON Web Token)** - A compact, URL-safe token format used for securely transmitting information between parties. Commonly used for authentication and authorization in web applications
- **Apollo-client** - State management library specifically designed for working with GraphQL APIs. It helps your app fetch, cache, and manage data from a GraphQL server efficiently
- **Concurrently** - Node.js tool that lets you run multiple commands (scripts) at the same time in a single terminal

The full list of dependencies can be found in the **package.json** file

---

## Contents

- [Installation](#installation)
- [Usage](#usage)

### Installation

1. Clone the repository:

```shell
git clone https://github.com/labattaria/job-board-client-ts.git
```

2. Install project dependencies:

```shell
cd job-board-client-ts
npm install
```

### Usage

Start the server using the following command:

```shell
npm start
```

This will start the server and also watch for changes in watch mode, generating outputs into the folder at the path src/generated/
Server will be located at **http://localhost:3000/job-board-client-ts/**
