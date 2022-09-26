# CMPG-323-Overview---31586872

## Repositories for Projects:
### Project 2: https://github.com/Hugovs2000/CMPG-323-Project-2---31586872.git
- Contains the files for the API
- More detail provided in project 2 repo README
### Project 3: https://github.com/Hugovs2000/CMPG-323-Project-3---31586872.git
- Contains description of Project 3, as well as the link to the repository that contains the code.
- More detail provided in project 3 repo README
### Project 4: https://github.com/Hugovs2000/CMPG-323-Project-4---31586872.git
- More detail provided in project 4 repo README
### Project 5: https://github.com/Hugovs2000/CMPG-323-Project-5---31586872.git
- More detail provided in project 5 repo README

<img src="RepoDiagram.png" alt="Repo Diagram">

## Branching Strategies:
- For each project a Main branch will be used to host the most current version.
- There will be a Develop branch which will be used to make changes.
- The two branches will be merged to form the most current version.

<img src="Branching.svg" alt="Branching Diagram">

## .gitignore file uses:
### Project 2: 

The .gitignore file was used to ignore the appsettings.json file since it contains the connection string to the database used which also contains the username and password of the connection.

### Project 3: 

The .gitignore file is in the visual studio iteration where it ignores the necessary visual studio files and it is also altered to ignore the appsettings.json file which contains the connection string of the database used.

## Storage of credentials and sensitive information:
Credentials and sensitive information will be stored by encrypting the password when storing it in the database and decrypting it when needed. Other sensitive information can be added onto the .gitignore to be ignored when committing the work.

## Reference List:
### Project 1:

Anon. 2016. A Practical Guide to Using .gitignore. https://www.pluralsight.com/blog/software-development/a-practical-guide-to-using--gitignore Date of access: 4 Sept. 2022.

Anon. 2022. Ignoring Files. https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files Date of access: 15 August 2022.

Haddad. 2022. What Are the Best Git Branching Strategies. https://www.flagship.io/git-branching-strategies/#:~:text=A%20branching%20strategy%2C%20therefore%2C%20is,interact%20with%20a%20shared%20codebase Date of access: 14 August 2022

### Project 2:

Anon. 2022. Gitflow Workflow. https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow Date of access: 14 August 2022.

Larson, Q. 2022. HTML new line – how to add a line break with the
tag. https://www.freecodecamp.org/news/html-new-line-br-tag-line-break/#:~:text=Adding%20line%20breaks%20in%20your,put%20it%20within%20your%20code. Date of access: 7 Sept. 2022.

Lurade, M. 2022. Store and read connection string in appsettings.json. https://www.connectionstrings.com/store-and-read-connection-string-in-appsettings-json/ Date of access: 4 Sept. 2022.

Nolle, T. 2021. The 5 essential HTTP methods in RESTful API development, SearchAppArchitecture. https://www.techtarget.com/searchapparchitecture/tip/The-5-essential-HTTP-methods-in-RESTful-API-development Date of access: 5 Sept. 2022.

smn.tino. 2018. Using .gitignore file to hide appsettings.json does not actually hide it. https://stackoverflow.com/questions/49930776/using-gitignore-file-to-hide-appsettings-json-does-not-actually-hide-it

W3Schools. N/D. HTML Images. https://www.w3schools.com/html/html_images.asp Date of access: 6 Sept. 2022.

### Project 3:

WilliamDAssafMSFT. 2022. Create Tables (Database Engine) - SQL Server | Microsoft Learn. https://learn.microsoft.com/en-us/sql/relational-databases/tables/create-tables-database-engine?view=sql-server-ver16. Date of access: 16 September 2022.

SQL UNIQUEIDENTIFIER Data Type - Dofactory. 2022. SQL UNIQUEIDENTIFIER Data Type - Dofactory. https://www.dofactory.com/sql/uniqueidentifier. Date of access: 17 September 2022.

Dot Net Tutorials. 2022. Generic Repository Pattern in C# with Examples - Dot Net Tutorials. https://dotnettutorials.net/lesson/generic-repository-pattern-csharp-mvc/. Date of access: 20 September 2022.

Antti K. Koskela. 2022. How to fix "No database provider has been configured for this DbContext" in EF Core. https://www.koskila.net/fixing-no-database-provider-has-been-configured-for-this-dbcontext-in-entity-framework-core/. Date of access: 22 September 2022.

Repository Pattern In C# . 2022. Repository Pattern In C# . https://www.linkedin.com/pulse/repository-pattern-c-pawan-verma/. Date of access: 23 September 2022.

tdykstra. 2022. Implementing the Repository and Unit of Work Patterns in an ASP.NET MVC Application (9 of 10) | Microsoft Learn. https://learn.microsoft.com/en-us/aspnet/mvc/overview/older-versions/getting-started-with-ef-5-using-mvc-4/implementing-the-repository-and-unit-of-work-patterns-in-an-asp-net-mvc-application. Date of access: 25 September 2022.
