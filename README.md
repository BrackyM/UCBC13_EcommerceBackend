# Braxton M | UCBC13_Ecommerce Backend | README

The objective of this Ecommerce Backend is to learn more around Object-Relational Mapping to learn about more data management with complex applications. ORM typically makes task manageable by using JavaScript to interact across databases, migrate existing data, and use several different forms of databases

Sequelize is used heavily within databases to make ORM more accessabile and easy to follow.


## Acceptance Criteria

```md
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

## Installation & Usage

This project uses Node.JS as well as a collection of other packages including sequelize and mysql2, featured in the package-json. To install the packages type in your terminal `npm i`.

Create an `.env` file to store user information for SQL connection set up like the following:

```md
DB_NAME=''
DB_USER=''
DB_PW=''
```
Once installing the packages and setting up your `.env` file, navigate to your gitbash terminal and enter `mysql -u root -p` to access the mysql shell command line. 

Within the mysql shell command you will need to enter `source db/schema.sql` to set up the database. You will then type `quit` and then enter within the gitbash terminal `npm run seed` to seed the database you just created

To run the program type in your console `nodemon server.js` to run the program.

You will then have your server live and can open up the Insomnia app to test out different `GET` , `POST` , `PUT` , and  `DELETE` paths.

Note: Program is ran through viewing in insomnia, mysql shell,  and the Gitbash terminal within Visual Studio Code.


## Screenshot

Screenshot of the Application

* Insomnia View of Different GET commands set up
![App Screenshot](./assets/screenshot1.JPG)


## Links

- [Video Walkthrough](https://drive.google.com/file/d/14LCrl79AFrjxEUPydPW_ujI2Xnf17mKV/view?usp=sharing)
- [Github Project Repository](https://github.com/BrackyM/UCBC13_EcommerceBackend)

##  Contributors / Resouces Used

- UC Berkley in class activites