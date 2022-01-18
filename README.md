<h1 align="center">LC Physical Education Site</h1>

E-Commerce Web App for purchasing resources to support Physical Education at Secondary School, for both teachers and students.

Code Institute - Final Milestone Project (4) - Full Stack Frameworks With Django

This project is hosted on Heroku => [View the live project here.](https://leavingcertpe.herokuapp.com/)

Purchases can be made with the Stripe test credit card:
* **credit card:** 4242 4242 4242 4242
* **expiration date:** Any future date
* **CVC:** Any 3-digit number
* **ZIP:** Any 5-digit number

A site for teachers and students to use, to support the teaching and learning of LCPE in Ireland. Providing a service and 
resources that can be purchased through the website.


<h2 align="center"><img src="static/images/responsive/amiresponsive.png"></h2>

## Table of Contents

- [Leaving Cert PE 

  * [Table of Contents](#table-of-contents)
  * [User Experience](#user-experience)
    + [User Stories](#user-stories)
    + [Wireframes](#wireframes)
  * [Information Architecture](#information-architecture)
   
  * [Design](#design)
    + [Color Scheme](#color-scheme)
    + [Typography](#typography)
    + [Logo](#logo)
    + [Icons](#icons)
    + [Images](#images)

  * [Features](#features)
    + [Main](#main)
    + [Shop](#shop)
    + [Product Page](#product-page)
    + [Cart](#cart)
    + [Checkout](#checkout)
    + [Account](#account)
    + [Admin](#admin)
    + [Custom Error Pages](#custom-error-pages)
    + [Features Left to Implement](#features-left-to-implement)

  * [Technologies used.](#technologies-used)
    + [Main Technologies](#main-technologies)
    + [Other tools](#other-tools)
    + [IDE (VSCode) Extensions](#ide--vscode--extensions)

  * [Testing](#testing)

  * [Deployment](#deployment)

  * [Local](#local)

    + [Pre-requisites](#pre-requisites)
    + [Recommended](#recommended)
    + [Steps](#steps)
    + [Heroku Deployment](#heroku-deployment)

  * [Credits](#credits)
    + [Code](#code)
    + [Tutorials](#tutorials)
    + [Acknowledgements](#acknowledgements)

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. <i>As a First Time Visitor</i>, I want to easily understand the main purpose of the site and learn more about what it can do for them.
        2. <i>As a First Time Visitor</i>, I want to be able to easily navigate throughout the site to find products and get an idea of what use it is for them.
        3. <i>As a First Time Visitor</i>, I want to be able to see how I can log in and purchase a product/service.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to log in easily, using the log in function.
        2. As a Returning Visitor, I want to be able click on each product and have an overview about them.
        3. As a Returning Visitor, I want to be able to purchase more than 1 product/service.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check back in to see if there is any new products/services.
        2. As a Frequent User, I want to check my order (if one is made).
        3. As a Frequent User, I want to be able to the contact the site to ask questions.

    -   * The website owner would like:
    + To be able to add new stock or update existing stock easily
    + users to be able to easily recover their account if they have lost their login details
    + for the website to appear clean, professional and high quality
    + for the website to work on all viewports, so customers can shop from any device
    + for the payment system to be secure and free of errors, such as orders going through without payment or payments being taken multiple times   

## User Experience

### User Stories

* As a new visitor, I would like:
    + to see the content and products on offer without having to register
    + to be able to easily register for the site
    + to be able to add items to my cart and save them for later
    + any items in my cart to remain there after I have registered for the site
    + to quickly and easily filter and search for particular items
    + to be able to sort displayed items by price or user rating
* As a repear visitor, I would like:
    + to easily login to my existing account
    + for my previously added cart items to remain selected
    + to be able to checkout quickly using my previously saved details
    + to be able to see my order history
    + to be able to review purchased items, and edit and delete my reviews
* All users would like:
    + to get feedback when I have completed an action on the site
    + for the cost and fees involved in an order to be transparent and not confusing in any way
    + to get a record/confirmation of a successful purchase
    + for purchases to be completed securely
    + be able to contact the website owners when necessary

        All Images were sourced from [google] (https://www.google.com)

*   ### Wireframes

Home Page  

<img src="static/images/wireframes/base_lhomepage.png">

Register Page  

<img src="static/images/wireframes/registerpage.png">

Log In  

<img src="static/images/wireframes/loginpage.png">

Profile Page  

<img src="static/images/wireframes/profilepage.png">

Add Category - People

<img src="static/images/wireframes/addcategory_people.png">

Add task - Event

<img src="static/images/wireframes/addtask_addevent.png">

## Information Architecture

As Django works with SQL databases by default, I was using SQLite in development. Heroku, however, provides a PostgreSQL database for deployment.

-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are black and white. The colours used are sharp, and contrast well with each other. 
        -   I chose these colours so that the images of the products would stand out better in the project. 

#### Typography
        -   The Lato font is the main font used throughout the whole website.
        This is a clear and easy font to read. It also looks professiona. 

    -   #### Imagery

-   ### Icons

[Fontawesome](https://fontawesome.com/) icons were used throughout the website. To enhance website performance, the entire Sass file was downloaded and any unused icons or elements commented out, rather than having to preload the FontAwesome CDN

-   ### Images

As noted, all of the project images were sourced from [Google](https://www.google.com)
