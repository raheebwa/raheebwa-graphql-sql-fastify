# Template for backend based on SQL, Fastify Server and GraphQL`

## Project Bootstrapping

### Required Libraries

For the development of our API we will install the following dependencies:

* fastify - this will be our http server
* apollo-server-fastify - this is the wrapper we are going to use so we can have fastify as our http server
* apollo-server-core - this dependency holds the main features of apollo server
* @graphql-tools/load - this will be responsible for loading our *.gql files (file system)
* @graphql-tools/graphql-file-loader - this one loads the type definitions from graphql documents
* graphql - the graphql implementation for javascript
* @graphql-tools/schema - creates a schema from the provided type definitions and resolvers

All the libraries mentioned above are the ones we will need to install to create our project, however we will still have to install others so that we can integrate our project with a database, in this series of articles I will use Sequelize ORM with SQLite database.

* sequelize - ORM
* sqlite3 - testing database
* mariadb - development database

### Support Libraries for Development

* sequelize-cli - for generating migrations
* nodemon - for running our project
* dotenv - for storing environment variables
