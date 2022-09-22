# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

## Description
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

Type `npm run seed` in the terminal to seed data to the database for the purpose of testing routes.

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
* [Project Video Demo - Start Server & Seeds run](https://user-images.githubusercontent.com/106945679/191847165-765dbf57-99a6-4cd2-8156-6e513bafbb63.mp4)
* [Project Video Demo - Insomia](https://user-images.githubusercontent.com/106945679/191847118-1d749f41-289c-4161-8b97-a1e9f17c460b.mp4)

## Final Thoughts
This week's project was not hard at all since it was mainly refactoring codes and putting correct functions in model and route files. The only hard time that I encountered was probably setting up functions like GET, PUT, DELETE, and etc in routes files; however, I overcame this issue by reading Express.js documentation and class materials. I personally don't like working on anything that's Express.js related because I feel like setting up routes are just tedious but I really like this project because I could see instant results when I used GET, PUT, DELETE functions in Insomia. Also I learned that it's very important to use correct relationship between models otherwise the database breaks. Overall, I feel more confident in building functions for setting up routes than before working on this project.

## Utilized Resources
[Sequelize Documentation](https://sequelize.org/docs/v6/core-concepts/model-basics/)
[Express.js Documentation](https://devdocs.io/express/)

## Contact
As always if you have any questions my GitHub user name is `hhealing123` and you can reach out to me at `hhealing123@gmail.com`!