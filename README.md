# ebook-store

## Overview
This is the backend of a webapp that allow users to read, write and sale novels. The backend is built using the C# programming language, utilizes Entity Framework for data management, implements PostgreSQL for database.

## Requirements
Before getting started, make sure you have the following prerequisites:
- Visual Studio or a similar C# IDE.
- PostgreSQL.

## Installation

1. **Clone the Project**: Begin by cloning the source code of the web application from GitHub or another source.

    ```
    git clone https://github.com/NguyenQuocBaoSaltedPeppered/EBookStore.git
    ```

2. **Open the Project**: Open the project using Visual Studio or your preferred C# IDE.

3. **Run the app**:

    ```
    dotnet build
    ```
    ```
    dotnet run
    ```

4. **Migrations Command**: Open a terminal or PowerShell and use Entity Framework to create the database tables and apply any necessary changes:
    ```
    dotnet ef migrations add InitialCreate
    ```
    ```
    dotnet ef database update
    ```

## Features

### Reading Novels

### Writing Novels

### Selling Novels

## Conclusion

This is a basic guide on how to use the backend of a web application for reading and selling novels. You can expand features and enhance security based on the specific needs of your application.