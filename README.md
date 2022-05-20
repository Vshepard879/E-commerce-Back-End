# E-commerce-Back-End
 
 # Description 
 
 Challenge 13 Object-Relational Mapping (ORM)

> A backend development application that creates a database for an e-commerce site that will utilize Object-Relational Mapping to interact with the database. The application is built using best practices from the RESTful CRUD operations concept. This is a command line application to manage an e-commerce database site using MySQL, which utilizes Node.js, MySQL2, Express.js, Nodemon, and Sequelize.


## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria 
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN that note appears in the right-hand column
- WHEN I click on the Write icon in the navigation at the top of the page
- THEN I am able to successfully create, update, and delete data in my database
## Demo of Project 
Part 1 - https://drive.google.com/file/d/1ABEIGiS7iAkXb27a6-LBm71TUlLLP_af/view
<br>
Part 2 - https://drive.google.com/file/d/1mimCi3kcBpj6x7m8Ke2vz1mYprX2nmAm/view

## Install
To install the dependencies you run:
```sh
npm install
```
If you plan on editing of the data, Nodemon is a helpful tool which can be downloaded with: 
```
npm install --save-dev nodemon
```
Please review <a href ="https://www.npmjs.com/package/nodemon">Nodemon</a> documentation if you are unfamiliar with the package.

***
## Usage
Run the following command at the root of your project starting with:
```
mysql -u root -p
``` 
Next, enter your password for MySQL. Once you are in your server run: 
```
SOURCE db/schema.sql
quit
``` 
Then run:
```
npm run seed
```
Finally, choose between running: 
```
npm start
OR
nodemon server.js
```
You can download <a href="https://insomnia.rest/download">Insomnia</a> to manipulate/test the data with the GET, POST, PUT, DELETE request.