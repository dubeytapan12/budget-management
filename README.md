# budget-management
Complete video series for Budget Management Project from scratch.  We will use Angular 15, .Net 6 , Angular Material, Entity framework core etc.

![screens-collage](https://user-images.githubusercontent.com/13220497/209772198-3a93c5d6-d3da-44ec-85ea-7794bea694d7.png)


<h1>Prerequisite</h1> -

Node JS, NPM, Angular CLI. you can follow my other video to install this in just 5 min. 

https://youtu.be/He31fkUHK0w

Editor -
Visual Studio or Visual Code 
https://visualstudio.microsoft.com/downloads/

MS Sql Server Management Studio 

<h1>SQL Scripts </h1>
https://github.com/dubeytapan12/budget-management/blob/main/BudgetManagement_mssql_create.sql
<h1>Entity Framework Core tools reference</h1>
<b>Reference</b>
https://learn.microsoft.com/en-us/ef/core/cli/dotnet<br/>
Run the following commands to verify that EF Core CLI tools are correctly installed:<br/>
dotnet ef

if tool is not installed than you can install it with below command: (only if above command doesn't work) <br/>
dotnet tool install --global dotnet-ef

<h1>dotnet ef dbcontext scaffold for our Budget Management </h1>
First install below package -</br>
Microsoft.EntityFrameworkCore.Core </br>
Microsoft.EntityFrameworkCore.SqlServer</br>
Microsoft.EntityFrameworkCore.Design</br>
Microsoft.EntityFrameworkCore.Tools</br>
