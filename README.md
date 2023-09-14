# E-Commerce

## Table of Contents
[General Info](#general-info)
[Technologies](#technologies)
[Installation](#installation)
[Usage](#usage)
[License](#license)
[Technologies Employed](#technologies-employed)

## General Info
We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Installation

To get started clone this repository using 


git clone git@github.com:brycehadl/E-Commerce.git

Both Node.js and MySQL must be installed on your computer.

Install dependencies 
terminal
npm init --y

terminal
npm install express sequelize mysql2

Open up MySQL shell and input 
terminal
source db/schema.sql

and 
terminal
use ecommerce_db

Then quit MySQL shell and input the following in your terminal
terminal
npm run seed

to start running application simply input 
terminal
node server.js

Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage

The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.

## License

License: MIT

## Technologies Employed
* JavaScript
* MySQL
* Node.js
* Inquirer.js
* Dotenv
* MySQL2

