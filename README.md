# Todo API

This is a project to learn dotnetcore web api. 
The projet is built following the steps mentioned in tutorial.

[First Web API](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.2)

## Migrations

Choose the [Dabase Providers](https://docs.microsoft.com/en-us/ef/core/providers/index)

Define the [DB Context](http://www.npgsql.org/efcore/index.html#defining-a-dbcontext).

Migrations are created using the below commands

```sh
dotnet ef migrations add InitialCreate
dotnet ef database update
```

## Run

```sh
dotnet run
```