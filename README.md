# Pralinörskan-app


Milestone project 4: Full Stack Frameworks with Django - Code Institute

![Image of responsive](https://timmy-bergkvist.github.io/Pralinorskan-app/media/pralinorskan.display.jpg)


**Target Audience**
 
Pralinörskan is a ecommerce app to sell pralines with different variations of flavors and quantity.

## Table of Contents
  * [UX](#ux)
    + [Project sections:](#project-sections)
    + [User Stories](#user-stories)
    + [Mockups](#mockups)
  * [Features](#features)
    + [Existing Features](#existing-features)
  	+ [Features Left to Implement](#features-left-to-implement)
  * [Technologies Used](#technologies-used)
    + [Language](#language)
    + [Libraries and frameworks](#libraries-and-frameworks)
    + [Tools](#tools)
  * [Database structure](#database-structure)
    + [Collection Name:](#collection-name)
  * [Testing](#testing)
  * [Deployment](#deployment)
    + [Local deployment](#local-deployment)
    + [Heroku deployment](#heroku-deployment)
  * [Credits](#credits)
    + [media](#media)
    + [Acknowledgements](#acknowledgements)

## UX

#### Project sections:

  - Header and navbar:
    A logo that are displayed on the left side and on click will redirect the user to home page.

    Three links are displayed Home, Products and Special Offers and on click will redirect the user to home page,
    Special Offers page. Clicking products link a drop down menu will be displayed with different products alternatives.

    A cart logo that are displayed on the right side and on click will redirect the user to cart page.

    If user is logged in a user logo are displayed on the right side and on click a dropdown menu will be displayed
    with three options. Profile details, Order History and Logout.

    If user is logout a Login and Register links are displayed.
                       

  - Homepage: 
  Containing a welcome message and a button that will redirect the user to all product page.
  In the middle of the page there will be four images of the stores best selling products.
  
  - Products: Containing all products that the store is selling.
  
  - Product: Containing specific information and image about the product.

  - Sign up form: Containing a form that enables user to sign up for the app.
  
  - Login form: Containing a form that enables user to login for the app.
  
  - Shopping cart: Contains information on products that are posted by the user ready to be purchased, updated or deleted.
  
  - Checkout: Contains a form to be filled by the user to make the payment and delivery.
  
  - Profile: Containing user information and the options to edit user information.
  
  - Order history: Containing information of previous purchases.
  
  - Footer: Displays info and links to social medias.

#### User Stories

None registered customer:
- As a customer, I want to access the platform from a desktop, tablet and a smartphone.
- As a customer, I want to view several kinds of products.
- As a customer, I want to buy products.
- As a customer, I want to view a specific kind of product.
- As a customer, I want to update the amount of products in my cart.
- As a customer, I want to remove products in my cart.
- As a customer, I want to make online payments.
- As a customer, I want to see details of a specific product.
- As a customer, I want to receive orderdetails to my email.
- As a customer, I want to registrate for an account.
- As a customer, I want to login and logout of the account.

Registered customer:
- As a registered customer, I want to view order history from previous purchases.
- As a registered customer, I want to view all my products to see the total amount.

Admin user:
- As a admin, I want to add, remove and update products.
  
#### Mockups
  
  I have used Figma Mockups to visualize images I can work from.

- <a href="#" target="_blank">Desktop</a>

- <a href="#" target="_blank">Phone</a>

- <a href="#" target="_blank">Tablet</a>


## Features

#### Existing Features

- A registration form to sign up for the application.

- A login form to access the application to view profile details.

- A nav bar that displays a Logo, Home, Products, Vegan, Gluten Free, Special Offers, Login/Logout, Account and Cart urls.

- A hamburger menu button that will display options in phone and tablet mode.

- A personal profile page where the user can view profile details and order history.

- A products page where the user can view all available products.

- A product detail page where the user can view personal details about the product and add the product to the shopping cart.

- A choping cart page where the user can view order details, update and remove the amount of products in the cart.

- A payment page where the user can pay for the order.

#### Features Left to Implement

- ....................

- ....................

- ....................


## Technologies Used

#### Language

- <a href="https://en.wikipedia.org/wiki/HTML" target="_blank"> Html </a>
  
- <a href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets" target="_blank"> Css </a>

- <a href="https://en.wikipedia.org/wiki/JavaScript" target="_blank"> JavaScript </a>

- <a href="https://en.wikipedia.org/wiki/Python_(programming_language)" target="_blank"> Python </a>


#### Libraries and frameworks

- <p><a href="https://www.djangoproject.com/" target="_blank"> Django</a>- A python web-framework to build projects.</p>

- <p><a href="https://getbootstrap.com/" target="_blank"> Bootstrap</a>- A CSS library grid.</p>

- <p><a href="https://fontawesome.com/" target="_blank"> Fontawesome</a>- Provides icons.</p>

- <p><a href="https://fonts.google.com/" target="_blank"> Google fonts</a>- Custom font styling.</p>

- <p><a href="https://jinja.palletsprojects.com/en/2.11.x/" target="_blank"> Jinja</a>- A template language for python.</p>

- <p><a href="https://pypi.org/project/psycopg2-binary/#description" target="_blank"> Psycopg2</a>- Python PostgreSQL adapter.</p>

- <p><a href="https://jquery.com/" target="_blank"> Jquery</a>- Javascript library to simplify the code.</p>

- <p><a href="https://boto3.amazonaws.com/v1/documentation/api/latest/index.html" target="_blank"> Boto3 </a>- A library that enables python code to modify AWS service.</p>


#### Tools

- <p><a href="https://en.wikipedia.org/wiki/Heroku" target="_blank"> Heroku </a>- For hosting the application and deploy.</p>

- <p><a href="https://stripe.com/ie" target="_blank"> Stripe </a>- Payment platform to accept and process payments online</p>

- <p><a href="https://code.visualstudio.com/" target="_blank"> VS Code </a>- Code editor</p>

- <p><a href="https://www.figma.com/" target="_blank"> Figma </a>- A collaborative interface design tool.</p>

- <p><a href="https://en.wikipedia.org/wiki/Amazon_Web_Services" target="_blank"> Amazon Web Services</a>- A cloud computing services.</p>
  
## Database structure

I have used <a href="https://www.sqlite.org/index.html" target="_blank">SQLite 3</a> database for this project



 #### Collection Name:
 
- ....................

## Testing 

  - The responsiveness is run and tested at:
    - http://ami.responsivedesign.is/#

  - The HTML code is run and tested at:
    - https://validator.w3.org/#validate_by_input
    - If you run the code you will get bad value and text not allowed in element,
    this is because I'm using
    <a href="https://en.wikipedia.org/wiki/Jinja_(template_engine)" target="_blank"> Jinja (template engine)</a>
  
  
  - The CSS code is run and tested at:
    - https://jigsaw.w3.org/css-validator/#validate_by_input
    
  - The JavaScript is run and tested at:
    - https://jshint.com/  
    
  - The Python is run and tested at:
    - http://pep8online.com/
    - 

|**Feature type**|**Feature**|**Tests**|**Bugs**|
| :---: |:---:| :---:|:---:|
|..text..|..text..|..text..|..text..|
|Button|Add to Cart|Getting  the right items. Posts the right items|No bugs|
|Button|Shop Now|Sends the user to the right html|No bugs|
|Button|Navbar toggler|Displays all links. Sends the user to the right html|No bugs|
|Button|Login|Logs in the user to home page. Toast popup|No bugs|
|Button|Register|Registers the user. Toast popup. Registration confirmation email sent|No bugs|
|Button|Add to cart|Adds items to cart. Toast popup|No bugs|
|Button|Decrement/Increment|Adds the right amount|No bugs|
|Link|Login|Sends the user to right html|No bugs|
|Link|Register|Sends the user to right html|No bugs|
|Link|Navbar|Sends the user to right pages|No bugs|
|Link|Main logo|Sends the user to home page|No bugs|
|Link|Product detail|Sends the user to right page. Displays right item|No bugs|
|Structure|Navbar|Works in mobile and tablet view. Sends the user to right html.|Responsive is working. No bugs|
|Structure|Navbar toggler|Works in mobile and tablet view. Sends the user to right html.|No bugs|
|Structure|Content|Stays in the midle. Works in mobile and tablet view.|Responsive is working. No bugs|
|Structure|Footer|Stays at the bottom. Works in mobile and tablet view.|No bugs|

Stripe payment testing.

```shell
The hosted demo is running in test mode use 4242424242424242 as a test card number with any CVC + future expiration date.
Use the 4000000000003220 test card number to trigger a 3D Secure challenge flow.
Read more about test cards on Stripe at https://stripe.com/docs/testing.
```
|**NUMBER**|**BRAND**|**CVC**|**DATE**|
| :---: |:---:| :---:|:---:|
|4242424242424242|Visa|Any 3 digits|Any future date|
|4000056655665556|Visa (debit)|Any 3 digits|Any future date|
|5555555555554444|Mastercard|Any 3 digits|Any future date|
|2223003122003222|Mastercard (2-series)|Any 3 digits|Any future date|


  - Bugs

  - ..text..

    ```shell
       ..text....text..
       ..text....text..
    ```
  
## Deployment
  
  
 The hosting platform for this project is Heroku and can be run directly here: 
 https://pralinorskan-app.herokuapp.com/
  
  
To run this project you need the following tools installed:

  - <a href="https://www.python.org/downloads/" target="_blank"> Python3 </a>
  - <a href="https://code.visualstudio.com/" target="_blank"> VS Code </a> or a code editor that have a debug tool.
  - <a href="https://git-scm.com/" target="_blank"> Git </a>
  - <a href="https://en.wikipedia.org/wiki/Heroku" target="_blank"> Heroku </a>

## Local deployment
<details>

<summary>Click to see local deployment instructions</summary>

The following instructions are based on Windows 10 and VS Code editor.

> Instructions:

  I.    Clone the repository in Github
 ```shell
  git clone <repository name>.git
 ```

  II.   Install all the packages that are required
```shell
pip install python
pip install django
pip install django-allauth

For more information:
https://django-allauth.readthedocs.io/en/latest/installation.html

```
  III.   Use django-admin startproject <app-name> dot
```shell
  django-admin startproject pralinorskan_app .
```

  IV.   create a virtual environment with the command:
```shell
 python -m venv env
```

  V.   Activate an environment
```shell

virtualenv env
source env/bin/activate

For more information:
https://code.visualstudio.com/docs/python/environments
```

  VII.   Migrate the models to crete a database template.
```shell
python manage.py migrate
```

  VIII.   Create a super user to have access to the admin page.
```shell
python manage.py createsuperuser
```


  IX.   Run the application
```shell
python manage.py runserver

Open the website at http://127.0.0.1:8000
```

  X.   Set up environment variable keys.
```shell
os.environ.setdefault('SECRET_KEY', '<secrete key>')
os.environ.setdefault('DATABASE_URL', '<postgres key>')

""" STRIPE API Keys """
os.environ.setdefault('STRIPE_PUBLISHABLE', '<stripe publishable key>')
os.environ.setdefault('STRIPE_SECRET', '<stripe secret key>')

""" AWS API Keys """
os.environ.setdefault('AWS_ACCESS_KEY_ID', '<aws access key id>')
os.environ.setdefault('AWS_SECRET_ACCESS_KEY', '<aws secret access key>')

""" Email Keys """
os.environ.setdefault('EMAIL_ADDRESS', '<your email here>')
os.environ.setdefault('EMAIL_PASSWORD', '<your email password here>')
```

  XI.  Set up the env path to manage.py
```shell
from os import path
if path.exists("env.py"):
    import env

```

  XII.  Log into your admin account add the /admin path at the end of the url link.
```shell
http://127.0.0.1:8000/admin
```

</details>

## Heroku deployment

<details>

<summary>Click to see Heroku deployment instructions</summary>

This project is hosted using Heroku.

> Instructions:

  I.  Install Heroku
```shell
npm install -g heroku
heroku login
cd my-project/
git init
       
Existing Git repository:heroku git:remote -a <app name>
```

  II. Install the necessary requirements
```shell
pip install dj_database_url
pip install psycopg2-binary
pip install gunicorn
```

  III.  Generate a requirements file and then install from it in another environment.
```shell
pip freeze > requirements.txt
```

  IV. Seting up Heroku.
```shell
On the resources tab select:
Heroku Postgres Database
```

  V.  Setting up to connect to Heroku Postgres Database In settings.py.
```shell
Step 1 import dj_database_url

Step 2 comment out the default configuration.
#DATABASES = {
#  'default': {
#     'ENGINE': 'django.db.backends.sqlite3',
#      'NAME': os.path.join(BASE_DIR, 'db.sqlite3'),
#  }
#}

Step 3  replace the default database with a call to dj_database_url.parse
        And give it the database URL from Heroku.

DATABASES = {
        'default': dj_database_url.parse('postgres://<your database url>')
      }

Step 4 Migrate.
python manage.py migrate

step 5 Load the categories and products. 
It is important to do them in this order!

1. python manage.py loaddata categories
2. python manage.py loaddata products
3. python manage.py createsuperuser

Step 6 Put back everything as it was.
when everything is migrate and done remove the Heroku database config.
And uncomment the original so it doesn't end up in version control and then set up the databases like this.

if 'DATABASE_URL' in os.environ:
    DATABASES = {
          'default': dj_database_url.parse(os.environ.get('DATABASE_URL',''))
    }
else:
    DATABASES = {
          'default': {
          'ENGINE': 'django.db.backends.sqlite3',
          'NAME': os.path.join(BASE_DIR, 'db.sqlite3'),
        }
    }
```
    
  VI. Create a Procfile
```shell
echo web: python app.py > Procfile

web: gunicorn <your application name>.wsgi:application
```

  VII.  Login to Heroku and temporarily disable collectstatic,
        So that Heroku won't try to collect static files on deploy.
```shell
Heroku config:set DISABLE_COLLECTSTATIC=1 --app <your app name>
      
```
VIII. Set hostname of our Heroku app in settings.py
```shell
      ALLOWED_HOSTS = ['<your app name>', 'localhost', '127.0.0.1']
      
```
IX. Set the config variables in your Heroku settings.

|**KEY NAME**|**KEY VALUE**|
| :---: |:---:|
|AWS_ACCESS_KEY_ID|your aws access key|
|AWS_SECRET_ACCESS_KEY|your aws secret access key|
|DATABASE_URL|your database url|
|EMAIL_HOST_PASS|your email host password|
|EMAIL_HOST_USER|your email@gmail.com|
|HEROKU_HOSTNAME|your heroku hostname.herokuapp.com|
|SECRET_KEY|your secret key|
|STRIPE_PUBLIC_KEY|your stripe public key|
|STRIPE_SECRET_KEY|your stripe secret key|
|STRIPE_WH_SECRET|your stripe webhook key|
|USE_AWS|True|

 
 X. Deploy your application to Heroku
```shell
git add .
git commit -am "make it better"
git push heroku master
       
Existing Git repository:
heroku git:remote -a <app name>
```
 
</details>

## Credits
  
   #### media
  - The photos used in this site were obtained from:

    - https://pixabay.com/sv/
    
    - https://www.pngjoy.com/

    - https://www.pngwave.com/
    

   #### Acknowledgements
  - Inspiration for this project was obtained from:
    -  Code Institute Frameworks with Django.
    
    - https://nordicoil.se/eir-cbd-kraem-foer-psoriasis
    
    - https://www.templatemonster.com/blog/top-45-ecommerce-business-ideas/
    
I wanna say thank you to my mentor Oluwafemi Medale for helping me through this project.
