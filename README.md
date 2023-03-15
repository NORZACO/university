# university

README.md


This code is a Node.js application that sets up a GraphQL API server with Express, Sequelize, and GraphQL. It creates an API for managing students and schools, with the ability to perform CRUD (Create, Read, Update, and Delete) operations on both. To use this code, follow these steps:

1. Install the necessary dependencies:
   You'll need to have Node.js and npm (Node Package Manager) installed on your system. Once you have them installed, run the following command in your m install dotenv sequelize express express-graphql graphql

   `npm install dotenv sequelize express express-graphql graphql
   `
3. Set up your environment file:
   Create a `.env` file in the root directory of your project to store your environment variables, like your database credentials and the port for the server. Here's an example of what the contents of the `.env` file should look like:

   ```plaintext
   DB_HOST=localhost
   DB_USERNAME=my_db_user
   DB_PASSWORD=my_db_password
   DB_NAME=my_db_name
   DB_DIALECT=mysql
   PORT=3000
   ```


Access the GraphQL API:
After running the application, you can access the GraphQL API at `http://localhost:3000/graphql` (or the appropriate URL, depending on your chosen port). You can use the GraphiQL interface or a tool like Postman or Insomnia to interact with the API and perform CRUD operations on students and schools.
