# Object-Relational Mapping (ORM) Challenge: E-commerce Back End
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US $29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

The project for this week is to build the back-end for an e-commerce site. Express.js API will be used, and configure it to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, a walkthrough video that demonstrates its functionality will be created for this project, and all of the following acceptance criteria should meet.

Make sure to clone the following [starter code repository](https://github.com/coding-boot-camp/fantastic-umbrella) and make own repository with the starter code.
## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
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

## Installation & Usage & Tests
Type `npm init` in the terminal to get package.json.

Type `npm install` in the terminal to install dependencies for the project.

Type `npm run seed` in the terminal to populate the database.

Type `mysql -u root -p`, then `SOURCE schema.sql;` in the terminal to create `ecommerce_db` database.

Type `npm start` to initiate the application.

Note that there is no testing for this project!

## Table of Contents
* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation & Usage](#installation--usage--tests)
* [Project Demo](#project-demonstration)
* [Final Thoughts](#final-thoughts)
* [Utilized Resources](#utilized-resources)
* [Contact](#contact)

## Project Demonstration
[Project Video Demo]

## Final Thoughts

## Utilized Resources
[Sequelize Documentation](https://sequelize.org/docs/v6/core-concepts/model-basics/)

## Contact
As always if you have any questions my GitHub user name is `hhealing123` and you can reach out to me at `hhealing123@gmail.com`!