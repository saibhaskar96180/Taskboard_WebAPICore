# Taskboard_WebAPICore

1, First We need to Install .NET Core SDK Latest
2, Create Web API Using below command
     dotnet new webapi
3, Run the application
     dotnet run
4, Install the below extension
     1, C#
     2, Nuget Package manager
5, Install Entity Framework
      dotnet tool install --global dotnet-ef
6, Add package Entity Framework Design
     dotnet add package Microsoft.EntityFrameworkCore.Design 
7, Execute the below command form verify the EF Installation
     dotnet ef
8, Enter scaffold command 
      dotnet ef dbcontext scaffold "connectionstring" Microsoft.EntityFrameworkCore.SqlServer --output-dir Models
(dotnet ef dbcontext scaffold "Data Source=(localdb)\MSSQLLocalDB;Initial Catalog=AzureBoard;Integrated Security=True" Microsoft.EntityFrameworkCore.SqlServer --output-dir Models)
9, For Generating bd context only in the folder
     dotnet ef dbcontext scaffold --context-dir Models
10, Create the controller also complete the steps in the middleware
