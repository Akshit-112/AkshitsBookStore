2023-10-30 2233
Created .Net 5.0 Web Application, enabled Individual account type under the authentication while creating the project (AkshitsBookStore)

2235
Commented out "sslPort": 44396 in launchSettings.json

2236
Created README.txt file and added all details in it

2238
Commented out  (options => options.SignIn.RequireConfirmedAccount = true) in startup.cs

2241
Created Github repository

2242
Reviewed Controller, Model, Views folders.

2243
Downloaded Bootstrap file for my theme from bootswatch.com
Renamed old bootstrap.css to bootstrap_old.css
Created new bootstrap.css and added styles in it
Replaced Site.css styles  with provided styles.

2250
In _Layout.cshtml , Attached bootstrap.css, modified nav classes from navbar-light to navbar-dark and bg-white to bg-primary
Removed text-dark from a elements
Added text-white-50 bg-primary properties to footer classes 

2305
Removed text-dark from _LoginPartial.cshtml
Ran project and output was perfct.

2309
Added Provided styles and scripts in _Layout.cshtml , from CSS_JS file.

2314
Added Dropdown menu next to privacy , in _Layout.cshtml

2319
Created 3 new projects using .net core class library
AkshitsBooks.DataAccess
AkshitsBooks.Models
AkshitsBooks.Utility
Copied Data folder to AkshitsBooks.DataAccess and deleted original

2323
Installed Microsoft.EntityFrameworkCore.Relational and Core.SqlServer packages

2327
Deleted Migration Folder

2329
Installed Identity.EntityFrameworkCore Package

2332
Deleted Class1.cs from all projects

2349
Got too many errors
Changed namespace in ApplicationDbContext.cs 
Solved error of IdentityDbContext by installing another version of Installed Identity.EntityFrameworkCore Package 
Built project after solving all errors, Built successfully

Date : 2023-10-31 
0003
Moved Models folder to AkshitsBooks.Models
Added Project Refrences to DataAccess and Models project

0006
Renamed Models folder to ViewModels
Changed Namespace in ErrorViewModel.cs

0017
Added project reference to Model
Tested application, ran successfully.

0022
Added Class in AkshitsBooks.Utility
Added Project References to Main project AkshitsBookStore
Added Project References to AkshitsBooks.DataAccess with another two projects

0036
Added new Area named Customer to Areas
Modified startup.cs as described in ScaffoldingReadMe.txt

0040
Moved HomeController.cs to Areas/Customer/Controllers folder
Deleted Data and Models folders of that folder

0044
Edited HomeController.cs 
Moved Home to Views inside Customer
Ran project, output is as same as PPT.

0053
Copied _ViewImports.cshtml and _ViewStart.cshtml to Customer Area
Modified _ViewStart.cshtml by changing path
Checked output , working perfectly

0105 
Added new area named Admin to Areas
Added View files in views folder 
Deleted Data and Models folders in that

0110
Deleted Controller folder from AkshitsBookStore project
Tested Application, ran perfectly

0125
Updated README.md


2023-11-06
1928

Started Part - 2
Built new solution 
Modified Appsettings.json

1939
Added Migrations In .DataAccess 20231107003624_AddDefaultIdentityMigration.cs 

1940
Reviewed SQL server and new tables

1948
Created Category class in .Models project and modified code 
Added new migration 20231107005302_AddCategoryToDb.cs

1953
Modified ApplicationDbContext.cs 
Re-ran the Migration by changing name to 20231107005302_AddCategoryToDbAgain.cs
Updated Database

1958
Created new folder named Repository in .DataAccess project
Created IRepository in that folder.

2000
Created IRepository interface in IRepository folder
Added CRUD methods in it

2003
Added class in Repository folder and implemented interfaces in it

2015
Added new class CategoryRepository.cs in Repository folder
Added new Interface ICategoryRepository.cs in IRepository folder

2019
Added Remaining code in CategoryRepository.cs 
Solved errors by adding using statements

2027
Added ISP_Call.cs and added code in that
Installed dapper package 
added remaining code

2036
Added new class SP_Call.cs and added connections via using statements in it

2038
Added new Interface IUnitOfWork
Added new class UnitOfWork

2043
made sure that public class implements the interface - UnitOfWork : IUnitOfWork
Modified both files and added using statements
Added " services.AddScoped<IUnitOfWork, UnitOfWork>(); " in Startup.cs

2049
Added new folder Controllers in Admin Area.
Added new controller CategoryController.cs in Admin Area.

2056
Added new Category View in Admin Area

2058
Created Index.cshtml in Category Folder and added code from provided files

2102
Modified _Layout.cshtml by changing navigation
Ran Application, Category is there

2110
Created category.js in wwwroot/js
Modified Index.cshtml and added @section call

2117
Added IActionResult to CategoryController.cs
Created Upsert.cshtml

2123
Added 2 partial views 
_CreateAndBackToListButton and _EditAndBackToListButton