# Tutorials-net6-0-WebAPIs-MongoDB

[Create a web API with ASP.NET Core and MongoDB](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-6.0&tabs=visual-studio-code)

## Web App ([site](https://nekogoo.github.io), [repo](https://github.com/NekoGoo/nekogoo.github.io))

Personal site for hobbies, aspirations, game news, game design, engine info, and patch notes.

### Useful Project Commands

Create the ASP.NET Core web API project

```bash
dotnet new webapi -o <project-name>
```

Add git-ignore file (standard as of 2020) (or [gitignore.io template](https://www.toptal.com/developers/gitignore/api/aspnetcore))

```bash
dotnet new gitignore
```

Install the .NET driver package for MongoDB

```bash
dotnet add package MongoDB.Driver
```
