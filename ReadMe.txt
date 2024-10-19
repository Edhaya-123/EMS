####Description:
     Employee Management System:
     The main objective of the project is to have two different Dashboard , one for employee and one for Admin. 

Admin : 

  -- Can create Employee, delete and view his details except downloading his salary details in pdf.

Employee:

  -- An employee can only view his dashboard and can download his salary details in pdf.

  -- DashBoard has Personal Details ,Professional details ,  Project details and Finance Details

###FrontEnd:

# Getting Started with Create React App

1.This project was bootstrapped with [Create React App].

2.Open the VS Code terminal and CD to the required drive.

3. Install Create React App globally:
   npm install -g create-react-app

4. Create a new React application:
   npx create-react-app (your directory name)

5. Navigate to the project directory:
   cd (your directory name)

6. Open the React project folder from File menu

7. Before starting the development Server====> 

     a) Your database is empty now , so to login into the dashboard, you need an admin and an employee. If there is a admin, he can login and create more employees. 
     b) So, to add an admin to your data base , you have to start the app with file ListEmployeeComponent. Lets change the starter to this file in App.js.
     c) Go to App.js at line no #### and change the {Login} to {ListEmployeeComponent} and then start the deployment server.
     d) While you add position , it has to be "Admin" if not he will become an employee. 
     e) Now that you have added an admin. Go to App.js  at line no #### and change {ListEmployeeComponent} back to {Login} .
     f) You can check your database table employee_login for the password. 		

8. To Start the development server:
   npm start
  

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any check errors in the console.

####BackEnd 

1) This project is built in SpringBoot.

2) For database , its JPA and MySQL.

3) After downloading the project in the designated folder(SpringWorkSpace), open SpringBoot and import the maven project .

4) Go to the File SpringbootBackendApplication.java fire in Src file under package com.example.springboot and execute it . 


