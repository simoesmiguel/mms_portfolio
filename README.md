# My portfolio

## About

This project's front-end was generated using Dhiwise as the main source.
Check the <a href="https://docs.dhiwise.com/"><img src="https://global-uploads.webflow.com/618e36726d3c0f19c9284e56/62383865d5477f2e4f6b6e2e_main-monogram-p-500.png" width="60" alt="DhiWise Documentation"></a>

This project has 2 sub-folders - frontend and backend.

1. Frontend

   All the design has been generated with [tailwindcss](https://tailwindcss.com/).
   Find all the theme related configuration inside tailwind.config.js

   This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

   This project is integrated with a [Tailwind CSS](https://tailwindcss.com/) setup, a new utility-first css framework, in an CRA environment. You can read more over on [Getting Started with Tailwind](https://tailwindcss.com/docs/installation).

   Figma: https://www.figma.com/file/7rSTh3w3EF5XVvEbi8BYeA/Portfolio?node-id=4%3A1630

2. Backend

   For the backend, [Prisma](https://www.prisma.io/) and [NestJs](https://nestjs.com/) is used.

   Prisma is next-generation Node.js and TypeScript ORM used to Perform database operations. For this project, SQLite database is used to store and retrieve data using Prisma.

   NestJs A progressive Node.js framework for building efficient, reliable and scalable server-side applications. For this project a backend server, accessible through REST APIs to store and retrieve data from the database.

## Versions of Technology

1. Nodejs version >= 14
2. NestJs version >= 9
3. Prisma version >=4

## Setup

Front-end runs on port:3000 and backend runs on port:8081.

1. from the root ` cd portfolio-front && npm i`
2. from the root `cd portfolio-backend && npm i`
3. create .env with variable `DATABASE_URL="file:folio.db"` file in `portfolio-backend` folder and run `npx prisma generate` when you are running the project for the first time.
4. from the root `npm start`

> Note: This project is setup in such a way that you can start the server and client from the root folder using `npm start`

## Folder Structure

```
├── portfolio
│   ├── portfolio-frontend --- client
│   ├── portfolio-backend  --- server
├── package.json
├── README.md
```

Detailed folder structure is inside the readme of respective folder.
