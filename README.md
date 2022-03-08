Install Visual Studio Code
Install the .NET Core SDK (you need 5.0(using in project) or newer)

Create the project
Open the command prompt (or terminal) and navigate to the folder where you would like to create the project. Execute the following commands:

mkdir TodoApi
cd TodoApi
dotnet new webapi
dotnet restore or dotnet build

install the IntelliCode
‘C#’ extension
Visual Studio IntelliCode(optional)

Install in memory database provider for entity framework core

Run the application:
dotnet run
Browse https://<localhost>:<port>/swagger/index.html
