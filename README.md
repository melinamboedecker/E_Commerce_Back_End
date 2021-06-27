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
* Run ```DROP DATABASE IF EXISTS ecommerce_db;``` and then```CREATE DATABASE ecommerce_db;``` in mySQL Shell to create the database in MySQL. 
* Run ```npde seeds/index.js``` in your bash terminal to seed the database
* Run ```npm start``` to initialize the server on your local machine, then you can interact with it using an API testing tool such as Postman or Insomnia.  

## Usage: 
  

![Screenshot](assets/e_commerce_backend.gif)


## License: 
Licensed under the [MIT](https://opensource.org/licenses/MIT) license. 

## Contributing: 
Feel free to contact me to contribute to this project. My contact information is listed below.

## Questions: 
GitHub: [melinamboedecker](https://github.com/melinamboedecker) 

If you have any additional questions, please contact me at melinamboedecker@gmail.com