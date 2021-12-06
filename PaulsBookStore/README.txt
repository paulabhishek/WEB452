Author: AbhishekPaul_0777040
Modified date: 03/Nov/2021

Project name: PaulsBookStore
Craeted Git repository
Downloaded bootstrap.css Darkly theme

added the bootstrap.css downloaded to bootstrap.css in wwwrot>lib>bootstarp>dist>css

replaced the main css file with css from BB

Changed the file name bootstrap.css from bootstrap.min.css in views>shared>_Layout.cshtml

Changed the nav class from nav-light to navbardark and bg-white to bg-primary

removed line 23 text-dark

removed the refernce _loginpartial.cshtml to text-dark

Ran project to reviewed the changes.

added css and script reference from CSS_JS in _Layout.cshtml.

Adding dropdown to the nav bar in views/shared/_layout.cshtml.

Built and run the project.

-------------------------------
Adding project and modifying
-------------------------------

Added three new projects to the application.

PaulsBookStore.DataAccess
PaulsBookStore.Models
PaulsBookStore.Utility

copied the Data folder and pasted to .DataAccess project

Installed Packages in PM.
Microsoft.EntityFrameworkCore.Relational
Microsoft.EntityFrameworkCore.SqlServer

deleted the migration folder

Installing Nuget package
Idntity.EntityFrameworkCore
Changed the namespace to PaulsBookStore.DataAccess.Data
Deleated all Class1.ca file in all projects

modified Views>Shared>Error.cshtml

Project - Add - project.
referenced DataAccess and models
Renamed models folder to ViewModels
Changed the ErrorViewModels.css namespace to .Models.ViewModels

Run the application and reviewd the errors
corrected the default refernces to ErrorViewModel to the new Model.ViewModels.ErrorViewModels
Ran again build successful.

Created CS.cs in Utility project
Modified the properties of the class.

Add project refernce to the main project

Added customers areato Areas

Ran the app and got a white page with Welcome message

Deleted the controller folder and upadted the GitHub repo.

Nov/ 14/ 2021
10 PM
created the migration and modified the database name.

Used the NuGet package manager console and added the migration.
changed to the correct default project and run - GO
created migration file 20211115042350_AddDefaultIdentityMigration.cs

Completed the migration and updated the datbase.

Updated the DB in the PM console.
11 AM Monday
created a database model and modified.

Added the migration via the PM console.

Re-ran the add-migration and reviewd the changes to the AddCtegoryTODB

Created the category.cs

Added a new folder Repository.

added a new item of type interface to the folder and named it IRepository.cs

Modified it si that it can be used on teh category class.

Created individual repos for all category and all potential models.
CategoryRepository.cs
ICategoryRepository.cs

Modified the ICategoryRepository.cs interface
Added a new interfafe in teh IRepository folder and ISP_Call.cs

Installing NuGet package for Dapper.

Added a new class in the Rep folder and implemented the ISP_Call interface.

Built and corrected errors


16/Nov

Started CRUD operation.
Started by adding new MVC controller CategoryController.cs
modified the cide to use the IUnitIfWork from the .DataAccess project.

Added new folder in Area/View with the same name as the controller.
Added a new index view pasted the code from Index View.txt from BB.
Successfully ran the app.

In the _Layout.cshtml moved the Category link to the content management drop-down
Modified the index.cshtml to add icons
deleted it and added the JS from BB into wwwroot/js

in the index.cshtml added teh @section call to the category.js script and ran the project.

Started to add Edit functionality using Upsert action

Added the IAction result to teh controller and added a view

copied the code from Category Upsert view.txt

Adding Partial view

in the general Views > shared folder added the partial voew for _CreateAndBackToListButton.cshtml and add the asp-action.
added another partial view for _EditAndBackToListButton and note the code addition of the @Model razor statement
Ran app navigated to category > create > new category works!
Replaced TITLE with @title

added a section call @section to call to the script
create Upsert POST action method in the CategoryController.cs
ran the app update does not work create works

HTTPDelete API in CategoryController.cs
implemented teh HTTPDelete with a delete method in category.js to add functionality to the application

Delete function added.
tested Edit and delete stil don't work
pushed changes to Github.


Part-3 section 1
Total hours: 2 hours
Added addProductRoDb migrations and updated the database 11:30 am

Craeted Cover Type CRUD and included teh methods used for category.
Added CoverType.cs in the Models folder.

Adding CoverType Repository.
Added class.
ICoverTypeRepository class
Added ICoverType Repo interface
Added CoverType to unitof work and Iunitof work.
Pushed the cover type to the DB.  12 Noon.

Performing CRUD opertaion Cover Type.
Added Cover Type NavBar.
Added CoverType Controller with all required actions methods.
Added cover type index and upsert view. 
delete Covertype using API call  12:30 

Product crud 3.2
added new product in models project
referencing the new product piece in the ApplicationDbContext.
adding migration for addProductToDb
added product to the repository.
Add Irepository interface, product class.
Modified unitof work and Iunitof work.
build the project no errors. 1 PM

started 3.2 Product CRUD Nov 24 3 PM
total hours: 2 hours
adding controller to teh area>admin>controller to perform CRUD.
added the IWebHostEnironment call to the using.

created ViewModel in models project and select list for category and covertype.
Modified the productVM class so it is public and installed MS.ASPnetcore.mvc.viewfeature package.
Modified product controller so that IActionResult Upsert calls to the productVm view model, included the using statement to the viewModels folder
Added index view.
modofied the product.js file.
modified the _Layout.cshtml and added the new product link.
saved and built teh project run time error while navigating to the product.

completed @ 5 PM

3.2 Product CRUD
24 Nov 9:31 AM
Time spent: 1 hour 30 min.

Created an Upsert.cs for products and modified in Areas >Admin>Views.

1 PM
Created an account in tiny.cloud copied the API key to initilize and added a function to validate input.
Made an folder in wwwroot>images>products. configured the Product upsert posy action method.
wrote the HTTP POST method.
Ran the app and tested.

End time: 2 PM

Dec 5th 10 am
hours spent: 7 hours
started fixing issues.
Category, CoverType, Product Edit wasn't working.
reviewd the slides and re-wrote Category.cs CoverType.cs and Product.cs
built and ran the app edit works 12 PM.

2 PM.
Used the github repo provided to check code against it for error.
no errors so far.
Products as demonstrated in class failed to ouput.
started debug but was not able to figure out the issue.

end time 5 PM










