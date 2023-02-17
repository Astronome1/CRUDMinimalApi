# MinimalApiApp
This is a minimalAPI project with CRUD operations on a user. It is a great starting point if you want to learn about MinimalAPI's in dotnet or if you want to quickly start making a MinimalAPI with a decoupled structure so that there are no necessary dependencies. 
# Getting Started
1. Clone the project onto your machine.
2. Create your SQL database by publishing the UserDB to your specific environment.
3. Add a connection string in the appsettings.json file and specifically in the "Default" : "" section in the application.
4. Run the project.
# Things To Note
1. This application makes use of the Dapper microORM to access data from the database for data speedup.
2. The UserDB project is loaded with some stored procedures that dapper will run, there is also some data seeding going on to make your job easier.
3. Enjoy working with this template😃
