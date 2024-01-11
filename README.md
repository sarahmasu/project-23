# Capstone Project - Django
<sub>Level 2 Task 23</sub>
## Table of Contents

1. [Introduction](#intro)
2. [Project Description](#description)

   2.1. [How the Project will Run](#runproject)
  
   2.2. [How to Use the Project](#useproject)
  
3. [Conclusion](#conclusion)
4. [References](#references)

## 1. Introduction <a name ="intro"></a>
This project was a capstone project from Level 2, Introduction to Software Engineering. The project was based on an online bookstore, where a user previous could purchase books to read on their account.

I have changed the project abit and removed purchasing books, but rather have the signed in users read the books on the website.

In the project I used the following langauges:
* Python
* HTML
* CSS
* Django
* Bootstrap

## 2. Project Description <a name = "description"></a>
The project was based on an another task about a store, in this case a bookstore, to add items on their online webpage of the products that are on sale. 

The project went through a number of changes before this project. The website consists of a home page, a blog, a library, a login and a sign up page. The user can navigate to these pages using the navigation bar provided at the top.

![MVC Framework Diagram](https://github.com/Icyfire315/CMPG-323-Project-3---32850123/blob/main/Assets/MVC%20Framework%20Diagram.png)


### 2.1. How the Project will Run <a name = "runproject"></a>
In order to run the project, you will need to create a django enviroment. Once you have created the enviroment, you will be able to run the program. If you do not create a django enviroment, you will not be able to run the program.

### 2.2. How to Use the Project <a name = "useproject"></a>
When you run the server, the program will run. Enter http://127.0.0.1:8000/home/ to redirect you to the home page of the website.

If you look on the navigation bar of the website, you will see links to other webpages:
    * Home (current page)
    * Blog
    * Library
    * Log in
    * Sign up

The Catalogue is a dropdown link, the navigation items do not link to another webpages. The only pages available for you to access is Home, Blog, Sign up, and Log in.
To access Library do the following:

* Step 1: Click on Sign up to create an user account. You will be asked to enter the following:
    *  First name
    *  Username
    *  Password
    *  Email address
  Once you have filed all the fields, click on the Sign up button. You will be redirected back to the home page.
* Step 2:  Once logged you can click on the 
* Step 3: Click on any of the three buttons and you will be take to their page, from here you can create, edit, view and delete items from the pages.
   * The Category page is where you create category items. When on the page you will see the category name, description, and the date it was created. If you click on the plus icon next the tile Category you can create an item. If you click on the pencil icon next to the category description you can edit the it, if you click on the eye icon it will display the information about the item, and if you click on the bin icon you delete the item.
   * The Zone page is where you create zones. On the page you will see the zone name, description, and date it was created. The UI is the same as the Category's UI.
   * The Device page is where you create items for devices. The UI consists of the device name, status, is active, and date create. The only thing that sets this page apart from the other two pages, is that it pulls information from both the Category and Zone pages. So when creating a new device You will have to enter the name of the device, select the category ID, select the zone ID, enter the status, and click on the checkbox to statue wether the device is active.
* Step 4: When you are done creating, updating, and deletintg items, log out.
* Step 5: If you wish to login click on the Login button, enter the your email address and password, to login.

## 3. Conclusion <a name = "conclusion"></a>
The API works together in the MVC framework to allow the user to see the data without having to *see it*. The point of this project is to see if I can take a project, from another repository, and contribute to the project, without changing the code, by adding to the code to make it more functional.

## 4. References <a name = "references"></a>
This is a neater, and more accurate, version of the Reference List document.