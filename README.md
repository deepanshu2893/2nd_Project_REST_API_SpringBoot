# Overview
My 2nd Project - REST API. This project was built using the SpringBoot Framework. It makes request to the server and the server responds with the name, age, posts, date of birth, etc. of the users in the database. Along with retrieving the users, this REST API can also POST users and posts for a user. All the CRUD operations are possible in this project which can either be connected to an in memory database like H2 (for development purpose) or with a relational database (RDBMS) like MySQL.
## Tools used
1. IDE - Intellij IDEA
2. Backend Framework - SpringBoot (Initialized using Spring Initializer)
3. FrontEnd Framework - NA
4. API Platform - Postman
5. Browser - Firefox (Chrome can also be used)
## How to use the REST API
1. Install IDE.
2. Install at least Java 20.
3. Install Docker (For MySQL)
4. Open the project with the IDE and start the application.
5. Once the application is booted, open a brower  go to http://localhost:8080/users. This should retrieve the users in the static list.
6. Before doing the above step rememeber to disable Spring Security in application.proeprties.
7. In order to add your own users, use H2 or MySQL. Add POST requests from the API client to save it in the database.
8. All CRUD operaitons can be performed in the same way.
