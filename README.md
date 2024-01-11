# Capstone Project - Django
<sub>Level 2 Task 23</sub>
## Table of Contents

1. [Introduction](#intro)
2. [Project Description](#description)

   2.1. [How the Project will Run](#runproject)
  
   2.2. [How to Use the Project](#useproject)
  
3. [What Changes can be made to Imporve the Website](#changes)
4. [Conclusion](#conclusion)
5. [References](#references)

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

The home page is the current page that you are on. 

![Home page](https://github.com/Icyfire315/project-23/blob/main/images/homepage.PNG) <br>

The Blog consists of post, posted by the admin, about changes, new addtions, and removals of any book or features on the website.

![Blog page](https://github.com/Icyfire315/project-23/blob/main/images/blogpage.PNG) <br>

The Library is where current and new books will be made available to user who have created accounts.

![Library page](https://github.com/Icyfire315/project-23/blob/main/images/librarypage.PNG) <br>

The Sign in page is where the user creates an user account. The Log in page is where users, who have created accounts, log into their accounts.

![Signup page](https://github.com/Icyfire315/project-23/blob/main/images/sign_up_page.PNG) <br>

The Log in page is where users, who have created accounts, log into their accounts.

![Login page](https://github.com/Icyfire315/project-23/blob/main/images/login_page.PNG) <br>

The Catalogue is a dropdown link, the navigation items do not link to another webpages. The only pages available for you to access is Home, Blog, Sign up, and Log in.

To access Library do the following:

* Step 1: Click on Sign up to create an user account. You will be asked to enter the following:
    *  First name
    *  Username
    *  Password
    *  Email address
  Once you have filed all the fields, click on the Sign up button. You will be redirected back to the home page.
* Step 2:  Once logged you can click on the Library page to view books on display (sorry for the terrible titles).

If you have already have an account do the following:
* Step 1: On the navigation bar click on Log in, enter your username and password. Then click on Log in button.
   
* Step 2: Then click on Libray to view the books on display (again sorry for the terrible titles).

If you try to click on Library you will be redirected to the Log in page, if you don't have an account click on Sign Up Now to create a user account.

## 3. What Changes can be made to Imporve the Website <a name="changes"></a>
Things I could add to improve the website:
   * Comment section: I could add a comment section to the posts to allow users to comment about the post.
   * Polls: To make the website more engaging I could add polls.
   * Forgot password: for users who have forgotten their password to change their password.
I could also prevent users from commenting on posts unless they are logged in.

## 4. Conclusion <a name = "conclusion"></a>
This website has gone through so many changes, some of these changes have improved the project by preventing users from accessing pages they should no access, creating poll questions and and their answers, creating blog posts, and (the best part of the project) creativity.

## 5. References <a name = "references"></a>
* PyLessons, 2022. Django messaging tool. [Online] Available at: https://pylessons.com/django-messaging [Accessed 25 December 2023].

* PyLessons, 2022. User login and logout. [Online] Available at: https://pylessons.com/django-login-logout [Accessed 25 Decemeber 2023].

* PyLessons, 2022. User registration & log in. [Online] Available at: https://pylessons.com/user-registration [Accessed 25 December 2023].

* GeeksforGeeks, 2022. How to User model Django?. [Online] Available at: https://www.geeksforgeeks.org/how-to-use-user-model-in-django/ [Accessed 23 Decemeber 2023].

* Thaqi, D., 2021. Create a Blog with Django. [Online] Available at: https://medium.com/geekculture/create-a-blog-with-django-60f529f1d8b6 [Accessed 28 December 2023].

* Anon., 2022. What is a "slug" in Django?. [Online] Available at: https://sentry.io/answers/slug-in-django/#:~:text=Slug%20is%20a%20term%20from,in%20a%20human%2Dfriendly%20form. [Accessed 28 December 2023].

* django, n.d. Using the Django authentication system. [Online] Available at: https://docs.djangoproject.com/en/5.0/topics/auth/default/#the-login-required-decorator [Accessed 29 December 2023].

* Jaya, 2023. How to use Login Required in Django: Restrict View Access. [Online] Available at: https://studygyaan.com/django/how-to-restrict-access-with-django-login-required-decorator-function [Accessed 2 January 2024].

* Perales, S., 2021. how to restrict pages in Django? if "@login required(login_url='login')" does not work. [Online] Available at: https://stackoverflow.com/questions/69099712/how-to-restrict-pages-in-django-if-login-requiredlogin-url-login-does-no [Accessed 30 December 2023].
