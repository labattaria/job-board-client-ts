**Читати іншою мовою: [Українська](README.ukr.md), [English](README.md).**

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

Це клієнт React/GraphQL/Apollo з [Job Board client](https://github.com/labattaria/job-board-client) репозиторію, але перенесений і перетворений на TypeScript

Клієнтський застосунок був трохи відрефакторений із використанням TypeScript, що додало типобезпечність коду

Він використовує генератор коду GraphQL TypeScript, який дозволяє нам генерувати TypeScript-типи та gql-graphql функції з нашої GraphQL-схеми, запитів та мутацій

Цей клієнтський застосунок — лише частина програми, друга частина (сервер) знаходиться в цьому репозиторії: [Job Board typescript server](https://github.com/labattaria/job-board-server-ts)

Застосунок у цьому репозиторії працює з сервером, розміщеним за адресою [https://render.com](https://render.com), за цією URL-адресою: [https://job-board-server-ts.onrender.com/graphql](https://job-board-server-ts.onrender.com/graphql)

## Залежностi, якi використовуються:

- **TypeScript** - Мова, що базується на JavaScript, додаючи статичні типи, допомагає розробникам раніше знаходити помилки та писати більш надійний код
- **GraphQL Code Generator** - Інструмент, який автоматично генерує TypeScript-типи (або типи інших мов) і шаблонний код на основі вашої GraphQL-схеми та операцій
- **Vite** - Швидкий і сучасний інструмент збірки, який забезпечує дуже швидку та гарячу заміну модулів (HMR) для розробки, оптимізований для фреймворків
- **React** - Бібліотека, що використовується для створення користувацьких інтерфейсів, особливо для односторінкових застосунків, де потрібен швидкий та інтерактивний досвід
- **GraphQL** - Основна бібліотека GraphQL
- **JWT (JSON Web Token)** - Компактний, безпечний для URL формат токена, який використовується для безпечної передачі інформації між сторонами. Зазвичай застосовується для автентифікації та авторизації у вебзастосунках
- **Apollo-client** - Бібліотека для керування станом, спеціально розроблена для роботи з GraphQL API. Вона допомагає вашому застосунку ефективно отримувати, кешувати та керувати даними з GraphQL-сервера
- **Concurrently** - Інструмент Node.js, який дозволяє запускати кілька команд (скриптів) одночасно в одному терміналі

Повний список залежностей можна знайти у файлі **package.json**

---

## Вміст

- [Встановлення](#Встановлення)
- [Використання](#Використання)

### Встановлення

1. Склонуйте репозиторій:

```shell
git clone https://github.com/labattaria/job-board-client-ts.git
```

2. Встановіть залежності проекту:

```shell
cd job-board-client-ts
npm install
```

### Використання

Запустіть дев-сервер за допомогою наступної команди:

```shell
npm start
```

Це запустить сервер, а також буде відслідковувати зміни в режимі watch, генеруючи вихідні дані у папку за шляхом src/generated/
Сервер буде доступний за адресою **http://localhost:3000/job-board-client-ts/**
