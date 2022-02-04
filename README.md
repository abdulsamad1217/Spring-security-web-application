# Spring-security-web-application

## Description
Spring security web application provides you customizable Authorization & Authentication framework. 
The framework uses azure technology and MySQL Workbench to run the application. 
Initially we need to deploy the server in the azure portal in which all the initializations should be given in the server portal before accessing the web application. 

## Flow
* Run the application(user your prefered IDE for spring-boot application)
* Localhost:8080
* Redirect you to the Microsoft login page(here login with your azure AD  username credential created following the tutorial above and enter the correct password)
* If the credentials are eneterd correct, you will be redirected to home page and can operate the CRUD features else It will reirect to error page showing message:- Sorry, you are not authorized to view this

## To run this application
* Fork & Clone the project.
* Setup Azure AD tenant-id, client-id, client secret and user group  and then add your credeentials in the file "Spring-security-web-application/src/main/resources/application.yml"
* Create Microsoft MySQL database instance(setup cloud server) and then replace connection string, username and password in file "Spring-security-web-application/src/main/resources/application.properties",  host the application as WEB Appp on Azure App service.
* Note:- You can also setup local MySQL server databse for testing purpose and use it's credentials to update application.properties file and run your project at localhost.

## Related Screenshots!

### Redirect URL configured on Azure AD
<img src="https://github.com/abdulsamad1217/Spring-security-web-application/blob/main/image/login.png" width ="1000px" height ="550px"> 

------------------------------------------

### Home
<img src="https://github.com/abdulsamad1217/Spring-security-web-application/blob/main/image/home.png" width ="1000px" height ="550px">
  

------------------------------------------

### Add Product
<img src="https://github.com/abdulsamad1217/Spring-security-web-application/blob/main/image/add.png" width ="1000px" height ="550px">

------------------------------------------

### Update Product
<img src="https://github.com/abdulsamad1217/Spring-security-web-application/blob/main/image/update.png" width ="1000px" height ="550px">

------------------------------------------

### Error
<img src="https://github.com/abdulsamad1217/Spring-security-web-application/blob/main/image/error.png" width ="1000px" height ="550px">

------------------------------------------

### Project Explanation 
https://youtu.be/3R1YJ5felsM

