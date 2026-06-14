# Employee Management System

A web-based Employee Management Mini System built with ASP.NET Core MVC and SQL Server.

## Technologies Used
- ASP.NET Core 8 MVC
- Entity Framework Core
- SQL Server (LocalDB)
- Bootstrap 5 + Bootstrap Icons
- Repository/Service Pattern

## Features
- Add, Edit, Delete, View employees
- Search by name or department
- Department management
- Form validation
- Clean responsive UI

## How to Run
1. Install Visual Studio 2022 + SQL Server + .NET 8 SDK
2. Clone the repo: `git clone <repo-url>`
3. Open `EmployeeManagementSystem.sln` in Visual Studio
4. Open Package Manager Console and run: `Update-Database`
5. Press F5 to run

## Database
The app uses Entity Framework Core Code-First migrations.
A seed script is available in `DatabaseScript.sql`.

## Project Structure
- `Models/` - Entity classes
- `Data/` - DbContext
- `Repositories/` - Data access layer
- `Services/` - Business logic layer
- `Controllers/` - HTTP request handlers
- `Views/` - Razor HTML pages
- `ViewModels/` - Data transfer objects for views
