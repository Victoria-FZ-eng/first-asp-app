# This is my fisr asp.net core app 

## Requirments

1. Install VSCode , Postman.
2. .NET 'CHECK FOR THE LAST VERSION', Angular & Entity Framework.
3. We'll be using HTML5, Bootstrap, CSS , Typescript, C# .

## Let's START

In your terminal `mkdir app_name` & `cd app_name` then use the below commands:

1. `dotnet new sln` to create the solution file.
2. `dotnet new webapi -o API` to create API project in output directory.
3. `dotnet sln add API` to add the API project inside the solution file .
4. Go to your IDE and open the folder you created or `code .` .

Note: for more information you can use the command `dotnet -h`.

- Make sure your on v.6.0 / copy Program.cs and startup.cs from here / and from launchSettings.json make sure that  ` "applicationUrl": "https://localhost:5001;http://localhost:5000" `.

5.  `dotnet dev-certs https --trust` for trusting the HTTPS development certificate. 
6. Back to powershell and `cd API` then run your app `dotnet run`.


