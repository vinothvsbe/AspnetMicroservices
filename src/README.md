# Documentation
Following are the command which we used to create API's

**Creating Solution**

``` Bash
dotnet new sln -n  aspnetrun-microservice  
```

**Creating API**

``` Bash
dotnet new webapi -o Catalog/Catalog.API
```

**Adding .csproj reference to Sln**

``` Bash
dotnet sln add Services/Catalog/Catalog.API/Catalog.API.csproj
```