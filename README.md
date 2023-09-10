# budget-management (.Net 8 Microservice Architecture, Angular 15, Docker, Kubernetes, Kafka )

Project Description:
The project aims to create a comprehensive home Budget management system with the following key features:

1. **User Signup and Home Management:**
   - Users can sign up for the system, providing a home name (e.g., Tapan-Home).
   - Within Tapan-Home, the first user registered will be the root user, with the ability to create additional users.
   - All users within Tapan-Home will be part of the same household.

2. **Account Management:**
   - Users can manage their financial accounts, including adding accounts with balances (e.g., HDFC: $20,000, SBI: $9,000, Pocket: $5,000).

3. **Category and Subcategory Creation:**
   - Users can create expense categories and subcategories.
   - Some categories may have subcategories (e.g., "Grocery" with subcategories like "Rice" and "Oil"), while others may not (e.g., "School Fee").
   - Users can create numerous accounts, categories, and subcategories as needed.

4. **Expense Tracking:**
   - Users can record expenses by selecting a category (and subcategory, if applicable), choosing the account, entering the amount, and specifying the expense date.
   - The system will store expenses associated with the home (e.g., Tapan-Home).

5. **Dashboard and Reporting:**
   - The system provides a dashboard for users to visualize monthly and yearly expense data through charts.
   - Users can also generate and download reports for further analysis.

This project will enhance household financial management, allowing users to efficiently track their expenses and monitor financial trends over time.

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
