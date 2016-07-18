# Chirper

<img src="http://i.imgur.com/w3zISX1.png" alt="" />

This week, you'll be building a remarkable and unique form of social networking. There's nothing else quite like it in social media and we are very pleased to have you working on it. 

Here's the deal. You need to build a social network where people can register for a free account and ~~tweet~~ chirp their thoughts in 240 characters or less to the world!

Let's get to work!

## App Requirements
- Users need to be able to register for an account.
- Users need to be able to log in to their account.
- Users need to be able to post "Chirps".
- Users need to be able to see "Chirps" that other users have posted.
- Users need to be able to like each others "Chirps".
- Users need to be able to comment on any Chirp.

## Pages
- Register Page
	- Registration fields
	- Register button
- Login Page
	- Email field
	- Password field
	- Login button
- Main Chirp Page
	- Chirp entry field
	- Chirp list
	- Commenting functionality
	- Like functionality

## Tasks

**Tuesday/Wednesday**

1. First! Take a second and create an Entity Relationship Diagram now, before you continue coding. This will go a long way in helping you build your application.
2. On your Windows machine, create a folder named `15-Chirper` in your `dev` folder.
3. Setup your Git workflow.
	- Initialize an empty git repository in `15-Chirper` by running `git init` in the command prompt.
	- Create a repository on GitHub called `15-Chirper` and follow the instructions to add a remote origin.
4. Open Visual Studio, create a new Solution called `Chirper`, with an ASP Web API project called `Chirper.API`.
5. From the Package Manager Console, add the following dependencies using these commands:
Install-Package Microsoft.AspNet.Identity.Owin 
Install-Package Microsoft.AspNet.Identity.EntityFramework 
Install-Package Microsoft.Owin.Host.SystemWeb 
Install-Package Microsoft.AspNet.WebApi.Owin 
Install-Package Microsoft.Owin.Security.OAuth 
Install-Package Microsoft.Owin.Cors 
6. In your models folder, create the necessary classes representing the entities you designed in step 1.
7. Create a `DataContext` class in a folder called `Infrastructure` that inherits from `IdentityDbContext`.
8. Configure your entity relationships as shown in todays video.
9. Create your database using Migrations. Remember - `Enable-Migrations`, `Add-Migration InitialCreate` and `Update-Database` are the commands.
10. Create your Web API controllers, one per Model class. 

**Thursday/Friday**

1. Create your Angular application as discussed in class.

## Turn in instructions
* Push your changes to GitHub 
* [Click here to create an issue in the class repository](https://www.github.com/OriginCodeAcademy/2016-SC-SummerCohort/issues/new?title=15-Chirper&body=1.%20Where%20can%20I%20find%20your%20repository%3F%20(Paste%20the%20url%20of%20your%20repository%20below)%0A%0A2.%20What%20extras%20could%20you%20add%20to%20this%20assignment%20given%20the%20time%3F%0A%0A3.%20What%20was%20the%20most%20valuable%20thing%20you%20learned%20in%20this%20assignment%3F)
	* Include a link to your repository in the description
	* Answer the questions filled out for you in the description
	