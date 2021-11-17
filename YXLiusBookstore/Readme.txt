2021 10/27
10:20am - Ready to start the assignment 2.
10:25am - Changed the _Layout.cshtml file, and used bootstrap.css.
10:29am - Instead of Yeti, I used sketchy theme instead.
11:41am - Deleted text-dark.
11:54am - Modified _Layout.cshtml again.
11:55am - Removed text-dark in the _LoginPartial as well.
11:56am - Added style sheet and JS script link to the _Layout.cshtml.
12:20pm - Sucessfully added the dropdown menu.
05:12pm - Added three new projects: DataAccess, Models, Utility.
05:20pm - Installed the three packages through the PM console.
05:32pm - Deleted the class files and moved the folders under the new projects
05:35pm - Ran it, and met several errors.

2021 11/01

11:32am - Changed something and still some errors.
11:45am - Still errors, decided to start over and build it again.
03:15pm - Built it again. Unfixed.

2021 11/03

10:37am - Finally found out the reason! Didn't intall the packages correctly. Should have installed them by the package manager.
02:34pm - Installed the packages correctly. 
02:41pm - Now the errors are gone. Except for the three expected ones.
02:43pm - Changed the reference and now the 3 errors are gone as well.
02:45pm - Changed the using statement, and no error anymore.
02:47pm - Added a class called SD.
02:55pm - Added project reference to the main project.
03:01pm - Added Customer area.
03:14pm - Ran the program and found no style applied to the index page.
03:16pm - Copied viewport and viewstart to the Customer area.
03:17pm - Now the style is applied perfectly!
03:20pm - Added admin area.




2021 11/08

12:07pm - Created the DB in project YXLiusBookstore, error alert!
12:08pm - Created the DB under project YXLiusBookstore.DataAccess project successfully.
12:10pm - 20211108170509 is the new migration file name entry.
12:16pm - Dived into the SQL Server Object Explorer, and found all my tables added through the entityMigration.cs
12:18pm - It can be run successfully.
12:23pm - Added a Category class into the Models project. And used it to add a new table.
12:26pm - The new migration file 20211108172542 is empty.
12:39pm - The class Category wasn't set public, so it was inacessable in the DbContext file.
12:45pm - Deleted the old migration file, add add the category to Db again.
05:01pm - Updated the database, now the catogory table is displayed on the sql server.
05:16pm - Added a Repository folder and an interface folder inside it.
05:23pm - Added an interface IRepository.cs file inside IRepository folder. And added CRUD methods.
05:30pm - Built a Repository.cs class.
05:31pm - Used the potential fixes to add content in this class.
05:36pm - Added constructors and Dependency Injection.
05:40pm - Added CategoryRepository class and ICategoryRepository interface.
05:46pm - Added Update method in ICategoryRepository interface
05:55pm - Added Upadate method in the class as well.
06:00pm - Created a new interface ISP_Call.
06:06pm - Installed the Dapper package.
06:14pm - Completed the ISP_Call interface.
06:15pm - Built the SP_Call class, and used the potential fixes again.
06:17pm - Added DI and constructor in the class.
06:40pm - Changed the implementation of the interface.
06:41pm - Added IUnitOfWork interface.
06:48pm - Completed the UnitOfWork class.
07:02pm - Modified the Startup.cs, but there is an error:"There is no implici reference conversion from class to interface".
07:09pm - Forgot the implement of interface in class. Now all errors are gone!

2021 11/10

09:17am - Changed Repository.cs, and built it again. 4 succeeded!
09:42am - Added CategoryController.
09:45am - Added a Category folder inside Views.
09:47am - Built an Index view.
09:50am - Copied the html code into the index.cshtml.
09:51am - Built it again. Ready to run it.
10:08am - Forgot to change the _Layout.cshtml. Now it can run successfully!
10:12am - Moved the Category to the dropdown menu.
10:34am - Added the JS file into the js folder.
10:35am - It works, but no category data inside for now.

2021 11/15
11:20am - Added Upsert.cshtml.
11:30am - Created a view for Upsert.
11:31am - Created a Button partial view.
02:25pm - Added a void Save method in IUnitOfWork.cs. Now the 3 errors are gone.

2021 11/16
10:40pm - In Upsert.cshtml, line 12, shouldn't the code be: Model.Id != 0, instead of Model.Id != null? (slide 17)

2021 11/17
09:26am - Started to build CoverType CRUD, same thing as the category CRUD.
09:27am - Added CoverType.cs.
09:33am - Added CoverTypeRepository.cs.
09:36am - Added the CoverTypeRepository interface.
09:39am - Added CoverType to the UnitOfWork.
09:40am - Added it to the UnitOfWork interface as well.
09:46am - Added CoverType to migration. 20211117144605.
09:49am - Updated the Database. 
09:58am - Added CoverTypeController.
10:04am - Added coverType.js
10:08am - Added CoverType to the layout. And let's run it for testing.
10:14am - Error occured when I tried to create a new cover type.

