# E-Commerce

Create a .NET Core Web API.

## Steps
- Fork [dotnet-training/E-Commerce](https://github.com/dotnet-training/E-Commerce) repository
- Implement updates to your repository. 

## Requirements
- Must have endpoints with CRUD operations (Create, Read, Update, Delete) for Products, Categories, etc.
- Must have normal users and admins.
- Admin can Read, Create, Update, Delete products and categories.
- Users can only read products and categories.


## Tools and frameworks
Use the following tools and frameworks:
- .NET 6
- Entity Framework Core with SQL Server database (Code First)
- JWT for authentication

## References
- [Create a web API with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio)
- [.NET 6.0 - JWT Authentication with Refresh Tokens Tutorial with Example API](https://jasonwatmore.com/post/2022/01/24/net-6-jwt-authentication-with-refresh-tokens-tutorial-with-example-api)
- [.NET 6.0 - Role Based Authorization Tutorial with Example API](https://jasonwatmore.com/post/2022/02/18/net-6-role-based-authorization-tutorial-with-example-api)


## Enhancements
- Use Dtos/ViewModels
- Use FluentValidation to validate endpoints inputs (using dependency injection)
- Use AutoMapper to map between Dtos/ViewModels and Entities (using dependency injection)
- Create base classes to avoid duplicate/repeated code
- Seed database with initial values.

### references
- [Create Data Transfer Objects (DTOs)](https://docs.microsoft.com/en-us/aspnet/web-api/overview/data/using-web-api-with-entity-framework/part-5)
- [.NET Basics: DTO (Data Transfer Object)](https://www.telerik.com/blogs/dotnet-basics-dto-data-transfer-object)
- [ASP.NET Core - FluentValidation](https://docs.fluentvalidation.net/en/latest/aspnet.html)
- [Getting Started with AutoMapper in ASP.NET Core](https://code-maze.com/automapper-net-core/)
- [C# Generics](https://www.tutorialsteacher.com/csharp/csharp-generics)
- [Data Seeding](https://docs.microsoft.com/en-us/ef/core/modeling/data-seeding)

