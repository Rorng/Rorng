To build a REST API with OpenID Connect authentication using .NET Core, follow these steps:

**1. Create a New ASP.NET Core Web API Project**
First, create a new ASP.NET Core Web API project using the .NET CLI or Visual Studio.

Using .NET CLI:

```
     dotnet new webapi -n OpenIDConnectAPI
     cd OpenIDConnectAPI
```
   
**2. Add NuGet Packages**
Add the necessary NuGet packages for OpenID Connect and authentication:
   
```
     dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
     dotnet add package Microsoft.IdentityModel.Tokens 
```
