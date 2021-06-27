# E_Commerce_Back_End
Back end database manager for e-commerce.  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## Description: 
This is an Express.js API that uses Sequelize to interact with a MySQL database. You can use API testing tools to interact with the e-commerce database. The database has tables for products, categories, tags, and product tags.

## Table of Contents: 
* [Installation](#installation)
* [Usage](#usage) 
* [License](#license) 
* [Contributing](#contributing) 
* [Questions](#questions) 

## Installation: 
* You will need to have Node.js and MySQL installed. 
* Run ```npm install``` in your bash terminal to install the dependencies.
* Update your MySQL user and password in the ``` .env.EXAMPLE ``` file then rename it to ``` .env ```. 
* Run ```DROP DATABASE IF EXISTS ecommerce_db;``` and then```CREATE DATABASE ecommerce_db;``` in MySQL shell to create the database in MySQL. 
* Run ```node seeds/index.js``` in your bash terminal to seed the database
* Run ```npm start``` to initialize the server on your local machine, then you can interact with it using an API testing tool such as Postman or Insomnia.  

## Usage: 
  
Use an API testing tool such as Postman or Insomnia to interact with the database.  Below are the GET, POST, PUT, and DELETE routes.  

To view all categories:
```GET http://localhost:3001/api/categories```

To view all products:
```GET http://localhost:3001/api/products```

To view all tags:
```GET http://localhost:3001/api/tags```

To view a single category:
```GET http://localhost:3001/api/categories/:id```
where ```:id``` is the id of the category you want to view

To view a single product: 
```GET http://localhost:3001/api/products/:id```
where ```:id``` is the id of the product you want to view

To view a single tag:
```GET http://localhost:3001/api/tags/:id```
where ```:id``` is the id of the tag you want to view

To create a new categrory:
```POST  http://localhost:3001/api/categories```
enter key/value pairs, refer to category table for column names


To create a new product:
```POST  http://localhost:3001/api/products```
enter key/value pairs, refer to product table for column names
/////ENTER tagIds INSTRUCTIONS/////

To create a new tag:
```POST  http://localhost:3001/api/tags```
enter key/value pairs, refer to tag table for column names

To alter a single category:
```POST  http://localhost:3001/api/categories/:id```
enter key/value pairs for the attributes you want to change

To alter a single product:
```POST  http://localhost:3001/api/products/:id```
enter key/value pairs for the attributes you want to change

To alter a single tag:
```POST  http://localhost:3001/api/tags/:id```
enter key/value pairs for the attributes you want to change


To delete a single category:
```GET http://localhost:3001/api/categories/:id```
where ```:id``` is the id of the category you want to delete

To delete a single product:
```GET http://localhost:3001/api/products/:id```
where ```:id``` is the id of the product you want to delete

To delete a single tag:
```GET http://localhost:3001/api/tags/:id```
where ```:id``` is the id of the tag you want to delete

![Screenshot](assets/e_commerce_backend.gif)


## License: 
Licensed under the [MIT](https://opensource.org/licenses/MIT) license. 

## Contributing: 
Feel free to contact me to contribute to this project. My contact information is listed below.

## Questions: 
GitHub: [melinamboedecker](https://github.com/melinamboedecker) 

If you have any additional questions, please contact me at melinamboedecker@gmail.com