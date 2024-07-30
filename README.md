# LibraryManagementSystem1
Project Setup

    Create a New Project:
        Use Visual Studio to create an ASP.NET Core MVC project.

    .csproj File:
        Include EF Core and MySQL NuGet packages.

    appsettings.json:
        Add the MySQL connection string.

    Program.cs:
        Configure services and the database context.

Folder Structure

    Data Folder:
        Create LibraryContext.cs to define the EF Core context.

    Models Folder:
        Create Employee.cs and Department.cs to define data models.

Database Migration

    Package Manager Console:
        Run Add-Migration InitialCreate and Update-Database.

Launch Settings

    launchSettings.json:
        Configure application URLs and environment settings.

GitHub Repository

    Initialize Git:
        Run git init in the project directory.

    .gitignore File:
        Exclude build and user-specific files.

    Commit and Push:
        Commit your code and push to a new GitHub repository.
