# Week 13: ORM E-Commerce Back-End

## Description

The task for this unit was to build out the back end for an e-commerce website using provided starter code and configuring a working Express.js API and Sequelize to interact with a MySQL database.


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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Animation and Link](#animation-and-link)
- [Installing Applications](#installation)
- [Walkthrough to Run](#usage)

## Animation and Link
  
💻 Below is the gif showing the functionality of the application:
  
![First Animation](./animations/First-animation-GET-routes-to-return-all-categories-all-products-and-all-tags.gif)

First Walkthrough Video <br>
https://app.screencastify.com/manage/videos/1x9R5mX0CiATtHRQyw2A

![Second Animation](./animations/Second-Animation-GET-routes-to-return-a-single-category-a-single-product-and-a-single-tag.gif)

Second Walkthrough Video <br>
https://app.screencastify.com/manage/videos/Ic2jIF1gIk3JeyLCVrTJ

![Final Animation](./animations/Final-Animation-shows-POST-PUT-and-DELETE-routes.gif)

Final Walkthrough Video <br>
https://app.screencastify.com/manage/videos/z9CGUS5waBONtw4uimxb
  


## Installing Applications 
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Walkthrough to Run  
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

`quit`

`npm run seed`
  
`npm start`


