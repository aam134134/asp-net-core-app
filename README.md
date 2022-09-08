# About Project
ASP.NET Core 6.0 with Angular project

# Setup OSX

[Download](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) and install .NET SDK package installer

```
# Create new project
dotnet new angular -o asp-net-core-app
```

# Build and Run

```
export ASPNETCORE_ENVIRONMENT=Development
dotnet build
dotnet run
```

# Install npm packages

```
cd ClientApp
npm install <package>
```

# Run "ng serve" independently (faster?)
```
cd ClientApp
npm start
```
