# ecommerceORM

## Description
This is an example of a backend for an e-commerce website. It utilizes an SQL database to provide tables and requested information when APIs are called. 

## Link to Repo

https://github.com/jrargent/ecommerceORM

## Link to Deployed Website

There is no website as this a node.js program. Instead, please clone or download the repo to run the program locally.

## Installation

Once the files are on your local machine, open the terminal and enter the command 'npm i' to download the dependencies and npm files necessary.

## Video Walkthrough

Please access a walkthrough of using this program at the following link:

https://drive.google.com/file/d/1OS-kOB2_SM_ni4oMVYcpzX8nOYDwUfJC/view


## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```


## Things I learned in this project
- Using Sequelize and MYSQL2 to connect API calls and database information
- Using Sequelize models to create database classes that could inherit properties
- I gained a better understanding of SQL tables and one-to-one and one-to-many relationships
