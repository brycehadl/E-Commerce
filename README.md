# E-Commerce

## Description

Internet retail, also known as e-commerce, plays a significant role within the electronics industry, as it empowers businesses and consumers alike to conveniently engage in online buying and selling of electronic products. In the latest available data from 2021, the industry in the United States alone was estimated to have generated the substantial amount of US$2.54 trillion, according to the United Nations Conference on Trade and Development. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

## Table of Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [License](#license)
5. [Technologies Employed](#technologies-employed)


## Installation

To get started clone this repository using 

git clone: git@github.com:brycehadl/E-Commerce.git

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

Live video:
https://drive.google.com/file/d/1GFaedmTj5jPjfCIAKNTDxb2R7QIbyJYn/view

## License

License: MIT

## Technologies Employed
* JavaScript
* MySQL
* Node.js
* Inquirer.js
* Dotenv
* MySQL2

