# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description

This is the homework for E-Commerce Back End.


## Link for the repo
[My homework](https://elcinkoyuncu.github.io/e-commerce-back-end/)

## Video for the application

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

![Demo](./Assets/GET.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

![Demo](./Assets/GET-1.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

![Demo](./Assets/POST-PUT-DELETE.gif)


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```


