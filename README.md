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

<img src="wireframes/">

Register Page  

<img src="wireframes/">

Log In  

<img src="wireframes/">

Profile Page  

<img src="wireframes/">


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


## Deployment

- All instructions regarding deployment are following process of deploying application on Linux. Some commands, particularly relating to Python or Pip will likely have some differences on MacOS / Windows (such as requiring `python3` or `pip3` while inside your virtual environment, as opposed to just `python` or `pip`)
- As always, look into the documentation for each program/environment mentioned if any uncertainty or issues.
## Local
Instructions to run the project on your local device

### Pre-requisites
- [Python 3](https://www.python.org/downloads/) - used to write the code and to run the project
- [PIP](https://pypi.org/project/pip/) - used to install packages
- [Git](https://git-scm.com/downloads) - used for version control
- [Gitpod](https://gitpod.io/) or any IDE of your choice - used to compile the code.
- [Stripe](https://stripe.com/en-ie) Account

### Recommended
- A virtual environment of your choice - used to contain all installations and packages and prevents clashing projects that might use the same package but different versions. Python 3 has a built-in virtual environment [venv](https://docs.python.org/3/tutorial/venv.html). This can be initialised using the command:

        python3 -m venv .venv

where `venv` is the name/path you are giving to the virtual environment

### Steps
1. Go to the project [repository](https://ctoweyburke/leaving-cert-PE)
1. Get the files used by using ***one*** of the methods below:
    i. Clone the repository by running the following command from your terminal: 

        git clone git@github.com:cjcon90/the_rhythm_box.git

    ii. Download the files used by clicking the 'Code' button located in the top section of the repository. Then select 'Download ZIP' and unzip the files in the directory of your choice.

1. Within your IDE/Terminal, navigate to the project directory where you located downloaded files/cloned the repo using (where `path/to/` is the files structure leading to the project folder)

        cd path/to/the_rhythm_box

1. Activate your virtual environment. If using Python's venv:

        source venv/bin/activate

1. Install all reqauirements from [requirements.txt](requrements.txt) file

        pip install -r requirements.txt

1. Migrate the models to create a database
        python manage.py makemigrations
        python manage.py migrate
1. Create a file `env.py` to store environment variables
1. Add environment variable in the format as shown below

        SECRET_KEY=<your-key>
        DEVELOPMENT=1
        STRIPE_PUBLIC_KEY=<your-key>
        STRIPE_SECRET_KEY=<your-key>
        STRIPE_WH_SECRET=<your-key>
        EMAIL_USER=<your-email>
        EMAIL_PASS=<your-email-password>

    - `SECRET_KEY` value is a key of your choice, to ensure appropriate seccurity measures, this can be generated using [Django Secret Key Generator](https://miniwebtool.com/django-secret-key-generator/)
    - `DEVELOPMENT` is set to `1` and is used in settings.py logic to ensure file is dynamic between local and remote setups
    - `EMAIL_USER` and `EMAIL_PASS` are used to send emails from the site admin email profile
    - `STRIPE_PUBLIC_KEY`, `STRIPE_SECRET_KEY` and `STRIPE_WH_SECRET` values are obtained from the [Stripe](https://stripe.com/en-ie) website
1. Run the application

        python manage.py runserver

1. Website should be accessible on either `http://127.0.0.1:8000` or `http://localhost:8000`

### Heroku Deployment

1. Create a `requirements.txt` file by pasting the following command into the terminal:

        pip freeze > requirements.txt

1. Create a `Procfile`  in the root directory and add the following code into it:

        web: gunicorn rhythmbox.wsgi:application

1. Push the code to GitHub by adding in the terminal:

        git add -A
        git commit -m "<commit message>"
        git push

1. Within Heroku, click on 'New' > 'Create new app' - give it a unique name and select the region closest to you

1. Set Heroku Postgres by going  to 'Resources' tab, search for 'Heroku Postgres' and select the 'Hobby Dev' free plan

1. Set config variables in Heroku

    | **Key**   | **Value**   |
    | --------- | ----------- |
    | AWS_ACCESS_KEY_ID | < your AWS access key ID > |
    | AWS_SECRET_ACCESS_KEY | < your AWS secret access key > |
    | DATABASE_URL | < your postgres database URL > |
    | EMAIL_HOST_PASS | < 16-character password from Gmail > |
    | EMAIL_HOST_USER | < your Gmail > |
    | SECRET_KEY | < your secret key > |
    | STRIPE_PUBLIC_KEY | < your stripe public key > |
    | STRIPE_SECRET_KEY | < your stripe secret key > |
    | STRIPE_WH_SECRET | < your stripe webhook key > |
    | USE_AWS | True |

1. Set up new database by
    - adding `import dj_database_url` within your `settings.py`:
    - locate `DATABASES` constant variable replace with following code:

```python
    if "DATABASE_URL" in os.environ:
DATABASES = {"default": dj_database_url.parse(os.environ["DATABASE_URL"])}
    else:
DATABASES = {
    "default": {
        "ENGINE": "django.db.backends.sqlite3",
        "NAME": BASE_DIR / "db.sqlite3",
    }
}
```

8. Backup current SQLite database by typing in the terminal:

        ./manage.py dumpdata --exclude auth.permission --exclude contenttypes > db.json

1. Migrate the models to Postgres database

        python manage.py makemigrations
        python manage.py migrate

1. Then use this command to load your data from the db.json file into postgres:

        ./manage.py loaddata db.json

1. Create a superuser (user with admin rights)

        `python manage.py createsuperuser`

    - enter an e-mail, username and password for the superuser

1. Add the hostname of Heroku app to allowed ALLOWED_HOSTS in `settings.py`:

        ALLOWED_HOSTS = ['<your Heroku app URL>', 'localhost]

1. Push the code to GitHub

        git add -A
        git commit -m "<commit message>"
        git push

1. Push the code to Heroku

        git push heroku main

1. Your site should be visible at your chosen Heroku URL


## Credits

### Code

- The entire website code was written based on the tutorial on the backend development milestone project by [Code Institute](https://codeinstitute.net)

-   The full-screen background image came from [Google](https://www.google.com) as it was easy to find the images that were useful for this project.

-   Bootstrap was used for code to ensure it is responsive when in various screen sizes. 

### Content

-   All content was written by the developer using the Code Institute Tutorial on the backend development milestone project by [Code Institute](https://codeinstitute.net).     The content has been adapted to suit the site needs in terms of the content.

-  I would have found this very difficult to write all this code and use the various packages without being supported by the Code Institute Tutorials.

-   I had severe issues with Gitpod as it affected my workspace and my requirements.txt files and uploading packages. Alot of hours was spent on line with Student Care to try and rectify these issues. And then when they were resolved, the next time the work space  was opened the same issues came up again!!! This took up alot of my time in this project. 

### Media

-   Icons were used from this site - [Font-Awesome](https://fontawesome.com/)

-   Images are used and have been referenced above.

### Acknowledgements

-   My mentor for help throughout the course.

-   Tutor support at Code Institute for their support, help, understanding and advice. Also, their patience with the ever running issue with Gitpod and its trickyness.

-   My family for helping me by giving me time  to complete the project.

-   Student care for supporting me as I got Covid in Dec over Christmas and them allowing me extra time to try to complete  my project. 

