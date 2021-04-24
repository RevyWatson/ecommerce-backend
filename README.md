# Ecommerce Backend

## Description

For this application I was provided starter code and tasked to build the back end for an e-commerce site. This application utizes Express.js API in tandem with Sequelize to interact with a MySQL database.

## Table of Contents

  - [Acceptance Criteria](#acceptance-criteria)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Questions](#questions)

## Acceptance Criteria
* When the user adds their database name, MySQL username, and MySQL password to an environment variable file they are able to connect to a database using Sequelize.
* When the user enters the schema and seed commands the development database is created and is seeded with test data
* When the user enters the command to invoke the application their server is started and the Sequelize models are synced to the MySQL database.
* When the user opens API GET routes in Insomnia Core for categories, products, or tags then the data for each of these routes is displayed in a formatted JSON.
* When the user tests API POST, PUT, and DELETE routes in Insomnia Core they are able to successfully create, update, and delete data in my database.

## Dependencies

This application utizes the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect the Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

## Installation

1. Fork and clone the repository.  
2. Open the command terminal on your machine.
2. Navigate through your file system to the location of the cloned repo.
3. To install the dependencies type “npm i”.
4. Open the gitignore file and type the following within:
```
node_modules/.DS_Store
jspm_packages
package-lock.json
.env
```
5. Open the dotenv file and add your local instance name and password like so:
```
DB_USER="your local instance's name here"
DB_PASSWORD="your mySQL Workbench password here"
DB_NAME=ecommerce_db
```
7. Return to the command line terminal and type, "node run seeds" to seed the database. Open mySQL Workbench to check that the database tables have been seeded.
8. Return to the command line terminal and type, "npm start" to activate the server.
9.Once the server is "listening" you can open Insomnia Core to manipulate and view the the data.

  ## Usage

Click the link to view the [Ecommerce]() in action!

  ## Questions

  Have questions or comments about this application?

  - Please feel free to email me at: garzoni.webdev@gmail.com
  - Or find me on GitHub at: [RevyWatson](https://github.com/RevyWatson)