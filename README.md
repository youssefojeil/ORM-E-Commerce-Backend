[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# ORM-E-Commerce-Backend
## Description
 A [Node.js](https://nodejs.org/en/) E-Commerce-Backend using Object Relational Mapping (ORM), [Sequelize](https://www.npmjs.com/package/sequelize), [MySQL2](https://www.npmjs.com/package/mysql2), [Express.js](https://www.npmjs.com/package/express) & the [dotenv](https://www.npmjs.com/package/dotenv) packages. Express.js, MySql2 & Sequelized are used in conjunction to set up a connection to the MySQL database & perform CRUD opperations.

## Table Of Contents
<li><a href="#installation">Installation</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#demo">Demo</a></li>
<li><a href="#license">License</a></li>
<li><a href="#questions">Questions</a></li>

## Installation
The modules used in this application are [Sequelize](https://www.npmjs.com/package/sequelize), [MySQL2](https://www.npmjs.com/package/mysql2), [Express.js](https://www.npmjs.com/package/express) & [dotenv](https://www.npmjs.com/package/dotenv).

To install necessary dependencies, run the following command:
```sh
npm install
```

## Usage
Must have [Node.js](https://nodejs.org/en/) downloaded

1. Create the database 
```
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;

```
2. Setup your .env file

3. Seed the database with the following command:
```
npm run seed
```

4. Start the server with either command: 
```sh 
node server.js
```
  or 
```
npm start
```

## Demo
[ORM E-COMMERCE BACKEND DEMO](https://drive.google.com/file/d/1LGyh0NYdOfn2fCixu51OZdTMqobIzFVI/view)


## License
This project is licensed under the MIT https://opensource.org/licenses/MIT


## Questions
If you have any feedback please feel free to reach out at my github https://github.com/youssefojeil or by email at youssef.ojeil@hotmail.com.
