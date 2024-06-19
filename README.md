# orm-e-commerce-backend

GIVEN a functional Express.js API

WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database

WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database


- - run `npm i` in the command line to indtall dependencies
- - create a `.env` file and input your information

DB_NAME = "ecommerce_db"
DB_USER = "postgres"
DB_PASSWORD = "..."

- - run `psql -U postgres` in the command line
- - run `\i db/schema.sql` and `\q` to quit
- - run `node seeds/index.js` in the terminal to populate the database with test data
- - run `npm run start` to start the server
- - use insomnia or postman to create api routes to create, read, update and delete data linking to products, categories, and tags

[Link to video](https://drive.google.com/file/d/1HZ2vh8RwEyO74DdDfGyvPlCubnJ-f3eh/view?usp=drive_link)
