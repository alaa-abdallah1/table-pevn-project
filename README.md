# TABLE - PEVN PROJECT
This is a web application built with PostgreSQL, Prisma, Node.js, Express, Vue.js, Tailwind, and GraphQL. It consists of two pages - the home page and the view details page.

## Live Demo
[Visit the live demo](https://crud-pevn-project.onrender.com)

## Screenshot

- Home Page

![image](https://github.com/alaa-abdallah1/table-pevn-project/assets/56931924/2c012c14-9633-4cbf-b4ec-a5040cdfaa05)

- View item page

![image](https://github.com/alaa-abdallah1/table-pevn-project/assets/56931924/71dc82f8-77fb-4a8e-a11a-4533d99d2ef0)


## Features
- A table that lists transactions
- Filter data by date range
- Pagination
- View the details page for each transaction

## Prerequisites
Before running the application, you need to have the following installed on your system:

PostgreSQL
Node.js
Yarn

## Project setup

**Clone the repository**

```
git clone https://github.com/alaa-abdallah1/table-pevn-project.git
```

**Switch to the repo folder**

```
cd table-pevn-project
```

## Backend

**Backend Setup**

```
cd backend && cp .env.example .env && npm install && npm run dev
```

**Don't forget to set the Database configuration in .env file**


**run migration and seed DB**

```
npx prisma migrate reset
```

**Frontend Setup**

```
cd frontend && cp .env.example .env && npm install && npm run dev
```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, open a PR.


## Code Owner 
This project was created by [Alaa Abdallah](https://github.com/alaa-abdallah1) 
