# MVC-Farm-Central
MVC C# - CRUD Website

Jordan Green. st10083222. PROG7311. POE. ReadMe

   * This Farm Central app was created with the purpose managing Employees and Farmers needs.

Description ~ This app was created for 2 types of users (Employees and Farmers) to create/login to an account. Farmers, once logged in, can save their product to the database.          
              I made this app using ASP.NET Core Web App (Model-View-Controller), which is required by Varsity College for this project.
              I faced an issue with hashing the password.

How to Install and Run the Project:
Visual Studio Code ~
Step 1  
        * Ensure that one’s computer has the capabilities to run Visual Studio
	* Ensure one has the necessary space to download the application.
	* Check the system requirements
Step 2  
        * Download Visual Studio
	* Download the bootstrapper filen
	* https://visualstudio.microsoft.com/vs/older-downloads/
Step 3  
        * Run the Bootstrapper to install the Visual Studio Installer
	* Choose workloads
	* Choose individual components – these are optional
	* Choose your language
	* Choose the installation location
Step 4 
        * Start coding and have FUN!!! 😊
Step 5  
        * Download code from GitHub
Step 6  
        * Open visual studio code, click on open project, and navigate to the folder which contains developed code
        * You have now accessed my built MVC app.
Step 7  
        * Search Microsoft SQL Server Management Studio 18 and click on the Microsoft link.
        * Scroll down to Download SSMS and follow the prompts.
        * Set up the Server name and finish the procedure.
Step 8  
        * Open Microsoft SQL Server Management Studio 18 and open the script provided, 
          then execute the database name, then execute the tables provided in the newly made database name, this will allow registration of new users and login features, plus adding farmer products.
          Also allows Employee and Farmer modules to be saved.
               ~ The tables provide in scrips are EmployeeUsers, FarmerUsers, and FarmerProducs.

# App features
(Version 1.2)

Updated features: 
- Ive improved the UI design and made it more user-friendly
- Ive added some design images and shortcut-icon/logo
- Ive moved the connection string to appsettings.json for security
- Ive made a video to demonstrate how the website operates 
       Youtube link here: https://youtu.be/xS3J8xg53kQ

 - When creating account, allows user to input Name, Surname, Email, Username, Password. These dettails are saved in DB tables.
 - Provides a connection to SQL Database which saves details/information to.
 - Can save product created by the Farmer.
 - Employee has the power to add new farmer, and view the list of all the products ever supplied by a specific farmer. This is done through a search bar. 
 
 ~ There are eight actions the user can take: 

 - (Sign-up)One button and two input function to type have been added
        1) Sign-up: Saves newly made users (Employees and Farmers) details to database.

 - (Login)One button and two input function to type have been added
        1) Login: Uses saved username and passord to see if account exists.

 - (Farmer Add Product)One button has been added
        1) Product Add: adds product created to the database with username.

 - (Employee Add Farmer)One button has been added, five inputs added as well.
        1) Farmer Add: adds new farmer to the database with all imputs included, username and password as well.

 - (Employee Filter Farmers)One searchbar and one four buttons have been added
        1) Filter Farmer: adds searchbar which searches usernames only. Also can narrow username, types of products and product name by descending order, simply click on the heading to implement this feature.

 - (Contact Us)One navbar button has been added
        1) Contact Us Page: A page which gives location to Farm Central with contact details included.

 - (About Us)One navbar button has been added
        1) About Us Page: A page which gives the necessary information to explain what Farm Central is about.

 - (Privacy)One footer button has been added
        1) Privacy Page: A page which gives the essential privacy information.

Error feautures: I tried to implement a hash but was unsuccessful
