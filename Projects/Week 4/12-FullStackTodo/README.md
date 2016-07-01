# Very Simple Todo App

For your weekend project you are going to extend your Very Simple Todo App to store Todo items in a SQL database via a REST API.

<img src="http://i.imgur.com/vhMYF1s.png" />

## Tasks
1. Make sure you have [SQL Server Express 2014](https://www.microsoft.com/en-us/server-cloud/products/sql-server-editions/sql-server-express.aspx) installed on your Windows machine.
2. Create a folder named `12-VSTDA-Backend` in your `dev` folder.
3. Setup your Git workflow.
  - Initialize an empty git repository in `12-VSTDA-Backend` by running `git init` in the command prompt.
  - Create a repository on GitHub called `12-VSTDA-Backend` and follow the instructions to add a remote origin.
4. Create a new Visual Studio solution in this folder called `VSTDA`.
5. Create an ASP.NET Web API 2 Project
6. Create and add properties to a class called `Todo.cs` in your Models folder.
7. Add a new `Infrastructure` folder in your API project.
8. Create and setup your Entity Framework DataContext class in a new `TodoDataContext.cs` stored in your `Infrastructure` folder.
9. Open Package Manager and run the migration commands shown in the video to initialize your SQL database via C#
10. Create a `TodoController.cs` file in your API project, following the wizard to generate an Entity Framework controller in the same way you saw in todays video.
11. At this point - your API is setup. Your challenge now is to integrate this API with your existing Angular application.

## Requirements
- Must be able to Create new Todo items (Which are ultimately stored in a database)
- Must be able to Read Todo items from the Database via the REST API you created.
- Must be able to Update Todo items (Changes must be saved to the database)
- Must be able to Delete Todo items (Items must be deleted from the database)

## Turn In Instructions
* Push your changes to GitHub using `git push origin master`
* [Click here to create an issue in the class repository](https://www.github.com/OriginCodeAcademy/2016-SC-SummerCohort/issues/new?title=12-VSTDA-Backend&body=1.%20Where%20can%20I%20find%20your%20repository%3F%20(Paste%20the%20url%20of%20your%20repository%20below)%0A%0A2.%20What%20did%20you%20enjoy%20most%20about%20this%20project%3F%0A%0A3.%20What%20was%20the%20toughest%20part%3F%0A%0A)
    * Include a link to your repository in the description
    * Answer the questions filled out for you in the description