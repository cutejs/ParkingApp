# Park Place

Park Place is a web application designed to solve the complex problem of parking and urban congestion. Park Place is a crowd sourced solution to parking in metropolitan areas, initially designed for a target market at the University in Tucson, Arizona. By allowing users to rent out their private parking spots we hope to solve the problem of underutilized parking infrastructure, while simultaneously generating passive income for users. Ideal for those who are visiting downtown areas, universities, sporting events, or may even be looking for a long term parking solution, Park Place is here to serve your needs!

## Getting Started

In order to get this program running on a local system for development or testing, you will need to follow several steps. If you would like to view an already working model, the application is hosted at 

* Clone the repository and run the schema.sql file located in the 'db' folder. This will set up the initial database necessary for the SQL tables. You will need a SQL command line or program to do this such as SQLPro or MySQL.
* Make sure to change the 'config.json' inside the 'config' folder to the information corresponding to your local SQL database.
* Execute the 'npm install' command when inside the cloned repository in order to install the necessary node packages.
* Run the server.js file to allow the sequelize ORM to setup the tables and their relations.
* Run the command "$ node_modules/.bin/sequelize db:seed:all" in order to run the datbase seeds
	* Use the command "heroku run sequelize db:seed:all --env production --app 'HEROKU-APP-NAME' to deploy the seeds for the database to the heroku server.

### Prerequisites


```
SQL
```
You will need a SQL program such as MySQL or SQLPro in order to create the database and view/seed the data within.

```

```

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

In 

## Built With

* [Node.js](https://nodejs.org/en/) - Command line interface and data manipulation
* [MySQL](https://www.mysql.com/) - Server software, create and manage database
* [Handlebars](https://handlebarsjs.com/) - Templating for HTML
* [Heroku](https://www.heroku.com/) - Server and database hosting for running application
* [Express](https://expressjs.com) - Web application and server structure framework

## Contributing

## Versioning

## Authors

* **Anindya Gupta** - ** - [anindya1234](https://github.com/anindya1234)
* **Christopher Clark** - ** - [christopheryc94](https://github.com/christopheryc94)
* **Darwood Martin** - ** - [ddmartin3](https://github.com/ddmartin3)
* **Luke Stewart** - ** - [linkadinkadoo](https://github.com/linkadinkadoo)
* **Kenneth Lanza** - ** - [klanza](https://github.com/klanza)


## License


## Acknowledgments

* Add Jan and TAs here
* Thanks to The Coding Bootcamp for the support and education
