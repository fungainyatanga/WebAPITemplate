# WebAPITemplate
Just a template for .net webApi documentation
Created this template because I started using a MAc from a windows 
and was having a hard time trying to figure out how to 
get things up and running when creating an Webapi with swagger. 

Maybe this might help someelse. 
add nuget package : Swashbuckle.AspNetCore -
Enabled middleware to serve generated swaggerui in the Startup.cs 
updated the launch settings

"profiles": {
    "IIS Express": {
      "commandName": "IISExpress",
      "launchBrowser": true,
      "launchUrl": "swagger",
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    },
    "WebApi.Template": {
      "commandName": "Project",
      "launchBrowser": true,
      "launchUrl": "swagger",
      "applicationUrl": "https://localhost:5001;http://localhost:5000",
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    }

#I will probably update some other things. 
When you run the project it launches: http://localhost:5000/swagger/index.html
