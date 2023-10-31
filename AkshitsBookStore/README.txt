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
