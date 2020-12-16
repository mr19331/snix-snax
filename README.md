# Snix-Snax Recipe Club

Snacks  are a staple for lunch-boxes, hikes and TV-time, and now they are important for working from home. Finding snack recipes  and new ideas for snacks, either online or in cookbooks can be time consuming and shop-bought snacks are often full of sugar, artificial colours or additives

. Snix-Snax Recipe Club  provides users with a never-ending flow of new snack ideas and recipes from club members. 

**Users of  the SnixSnax site**  can register to  share their favourite snack recipes, can create, edit and delete their own recipes, and view a library of recipes ( called a Recipe Box) they can  use and store other people's recipes, watch how to videos and buy cookbooks and cooking tools.
The snacks are categorised under several popular headings - Sweet, Savoury, Gluten- Free, Kids and Popular. 

**Owners of the SnixSnax site** have several opportunities for monetization
Commission can be earned as an amazon.com associate from advertising snack recipe books  or cookware 
Commission can also be earned from adding an ingredient shopping list for popular supermarkets ( Tesco, Ocado Sainsburys) so that users can quickly send a shopping request for the ingredients that they are missing 


![](https://res.cloudinary.com/mr19331/image/upload/v1607680940/Mockup-Generator_ygxaxn.png)

### link to the live website on Heroku project [Snix-Snax Recipe Club](https://recipe-manager-project.herokuapp.com/)

## Admin login is username admin pw 123xyz

### Concepts used in the Snix Snax Recipe Club project 

The website makes use of the **CRUD** model . CRUDis the acronym that refers to the four basic types of functionality Create, Read, Update and Delete
 Each of the four operations  is a request sent by a user that is relayed to the database in order to change the data in it or retrieve some part of it 

 **Create** is the operation of adding a new record to the data store – the user of SnixSnax site can add their own recipe 
 **Update** is the operation of changing one or more fields in existing records, the SnixSnax user can edit the recipe that they added.  
 **Delete** is removing a record – user can delete the recipe that they added. 
 **Read** is the most common CRUD operation – it is a request to retrieve information from the data without changing it – SnixSnax users can read the recipes on the website .

Using the CRUD model allows the data that is stored to be shared and used by website users and provides a more valuable user experience. The user gets to actively participate and the website is  dynamic and constantly changing. 

**DRY** is the acronym for Don’t Repeat Yourself this refers to the coding concept of creating code once and then reusing it to reduce time and labour and this has been used throughout the Snix Snax project 

The jinja formatting used in Flask allows a base template (base.html) to be constructed with code common to each of the pages. 
 The base template  in the Snixsnax site, supplies the navbar, side navbar ,navigation links and the footer to the remaining templates providing uniformity throughout the site and less work for the developer. 
 Category_type.html is a template that contains recipes filtered by category and makes use of only one page to display 5 different categories and respective recipes. 



### Project Flow Diagram

![]<img src="https://res.cloudinary.com/mr19331/image/upload/v1608022891/Project-Flow-Diagram_pqazqt.png" style="zoom:150%;" />

- [**Goals of the website**](#--goals-of-the-website--)
    + [User Goals](#user-goals)
    + [Site Owner Goals](#site-owner-goals)
- [UX](#ux)
  * [**User Stories**](#--user-stories--)
    + [Strategy](#strategy)
    + [**Scope**](#--scope--)
    + [**Structure**](#--structure--)
    + [**Skeleton**](#--skeleton--)
      - [**Wireframes**](#--wireframes--)
      - [**Surface**](#--surface--)
- [Features](#features)
    + [Existing Features](#existing-features)
    + [Features Left To Implement](#features-left-to-implement)
- [Defensive Design](#defensive-design)
- [Technologies Used](#technologies-used)
  * [**Testing**](#--testing--)
- [Security](#security)
    + [Authentication](#authentication)
  * [**Bugs /Problems during project development****](#--bugs--problems-during-project-development----)
- [Deployment](#deployment)
- [Credits](#credits)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgements](#acknowledgements)




## **Goals of the website**

#### User Goals

To  access an online source of  recipes for  snacks . 
To find snack recipes easily by searching or by category
.To be able to add a recipe to the site and to be able to edit or delete those recipes
To store a library of chosen or added recipes and to be able to access them easily.
To watch how-to videos for cooking techniques 
To buy cooking related gifts or tools for cooking

Navigation between site sections must be uncomplicated and clear for users 
Notification that  an action is  successful or unsuccessful must be provided to users.
 Buttons and links for user actions must be labelled and clear.

#### Site Owner Goals 

To provide users with a site that provides value so that they register and use the site regularly. 
To monetize the site so that users will purchase goods or take actions that create commission for the site owner. 

 To have a separate  admin-only section on the site for  team members  to edit or add categories etc.   

### Project Concept 

## UX

### **User Stories**

​          **As a new /first time  site user** 

​       I want to understand what  information this site is offering  immediately 

- I expect to be able to access the information that I want easily using conventional  image and link clicking methods
- I want to be able to access categories of recipes to save me time,  as well as searching by name
- I want to be able to visit the site easily on my phone and tablet as well as desktop
- I  don't want to be spammed because I have visited the site 
-  I don't want to be forced sign up for anything or  to give out my information unless I get value in return. 
- I may want to buy gifts from the site or  cookware 
- If I like thte site I might want to  watch videos that demonstrate cooking techniques etc.
- I want to see some information on the website owners so that I can decide if the site is reputable ( Contact information, privacy policy, About us)
- I expect to be able to connect with the social platforms that the brand is using so I can get further reassurance that they are reputable

**As a returning visitor/user to the site:**

- I want to be able to register quickly and give a minimum of personal information
-  I may not want to give my email just to register 
- If I make an error logging in I want to be alerted to my mistake 
- I expect any information I give to be secure and confidential 
- I expect to be able to login and logout easily and  to be able to find those links quickly
- I do not want other users to be able to edit or delete my recipes
-  I want to be able to add a recipe , edit it and delete it and I don't want the process to be complicated 
- I want to see clear instructions how to  take these actions 
- I want to see confirmation when I have successfully completed any of these actions 
- If I decide to delete one of my recipes I expect a warning in case I clicked the button accidentally 

**As the website owner/admin user:**

-  I want  the website to  provide valuable information for users so that they return frequently
-  I want users to stay on the site for as long as possible and to contribute fresh content to the site. 
-  I want the personal information provided by users to be secure and private
-  I expect the users of the site to be able to contact admin if they wish. 
-  I expect admin sections of the site to be secure and have  protected access
-  I want to be able to login and logout and to be able to easily and quickly add, edit or delete the information that is regulated by admin.
-  I want the processes of the site for admin and other users to be clearly indicated and laid out so that each action is easily navigated. 
-  I expect to be notified if I complete an action successful and to be given a warning in case I accidentally choose to delete something
-  I want the site to be stable and robust and function without problems 
-  I want to monetize the site so that it creates revenue 




#### Strategy

The primary function of the SnixSnax  site is to persuade users that they will receive valuable information in exchange for registering and using the site. If the  user goal is achieved,  the site-owner goal will  be met, that is to have users return many times so they can shop on site  and the site-owner earn commission from advertising.

#### **Scope**

The content and layout of the website is  to establish a means for the site owner to maintain an ongoing connection with users of the website, online ads are effective but a user has to see an advert several times before the site user makes a purchase. 
The SnixSnax recipe Club  encourages users to return frequently - it serves as a recipe repository and allows users to  add their own favourite recipes and to see what other users are adding to the site. 



#### **Structure**

The  Home page for SnixSnax Recipe Club is a simple landing page with a navigation bar and links for the user to Register or Signup to the site or to login if they are already registered.
 It is assumed a user will spend a  short time looking at the content
 The  search bar is prominent on the Home Page so that the user can find recipes quickly and only the most recent recipes that have been submitted are displayed.

A user is likely to spend  time on the site on

-  their Recipe Box page where they can view their collection of recipes 
-   on their Add Recipe Page where they can add recipes .

The monetization of the Home page is important because the user will not spend much time here, so every item must serve some function. - videos are a good way to catch the interest of a user and a selection is presented 




#### **Skeleton**

##### **Wireframes**

 [Wireframes](/WIREFRAMES.md)
 Design changes made from the original wireframes. 
 MaterializeCss allows for responsiveness in all versions. 
 The categories
 It was decided to leave all 3 videos in the mobile version - they did not make the page too long and users liked them.  

  

##### **Surface**

The appearance of the site is very important, if the site doesn't appear professional and appealing then the user may not go further and become a  regular user.
 The website is the shop- window for the site owner. 
There has to be a balance between content to attract users to register and use the site regularly and monetization.



## Features



#### Existing Features
**Navbar**   is in the conventional position on all desktop version site pages,contains links that are easy to read, and collapses to a convenient toggle menu icon on mobile version  The mobile and tablet toggle icon opens to a side navbar for users convenient viewing.
Both navbars serve 2 purposes 

1. Display links to the user to easily navigate to the page required to fulfill a function 
   Eg Register or Add A Recipe etc
2. . To control  user access to site pages

Navbar links are different for different user status:

- Unregistered users can see links to  Home Register, Login
- 
  Logged in  users links displayed are   Home, Profile, Add Recipe, Logout
- Admin users navbar links are  Home, Profile, Add Recipe, Manage Categories, Logout

**The Search Bar** with background image is the  first thing that a new user will see on the site. 
The background image is colourful and includes a short text explanation This section allows a new  user to understand what the site is about and try the site without scrolling through the page

User sees exactly what to do and how with minimal effort. Simple instructions, central location and minimal information requirement allows the user to get what they want easily
All users are welcome to use the search function but registered members receive more value.

Text is served in small chunks and images carefully selected for the most impact. 

**Registration Form and Login Form** The registration and login requirements are kept to the minimum for user convenience. Only a username and password are required . Text on the submit button reminds them of the action .A link below each form will return a user to the login page if they have already registered or to the register page, if they try to login without registering first.  

**Recipe Box** Each user can see the recipes that they have added to the site as a collection in their "Recipe Box"
Recipes are displayed as a card with the recipe name, date added and and image 
Buttons for Edit and Delete actions are displayed for each recipe, so the owner can easily access both actions 

**Add Recipe Form**

To add a recipe the user clicks on Add Recipe link from the navbar after logging in. 
The user can add the details of their recipe on this form.
Each field has an icon to indicate the action and  is clearly named with a placeholder and space allowed for text to be entered 
A dropdown is included for choice of category. 
The user is given the option to include an image URL  for uploading 
A datepicker is included for a user to add the date of the submission.
A large clearly marked button is displayed at the bottom of the form for submission

**Edit Recipe Form**

The original recipe form is displayed to the user with the entries
The user can edit the text in each field or change the date or select another category easily
2  large clearly marked buttons are displayed at the bottom of the form Cancel and Edit 
if the user has changed their mind and want to cancel they can do so or If they want to implement the changes they have made

**Admin Profile** 
**Manage Categories page** 
**Add Category and Edit Category**

**Footer** 

A simple footer is displayed at the bottom of the Home page 
Links to an About Us page, a Contact Us page and a Privacy Policy page 
These links are required for the site but are displayed in the footer to avoid cluttering the main navbar.
Social links to Facebook, Youtube and Instagram and Twitter platforms are shown in the footer section. 

####   Features Left To Implement

- ​      Add  functionality to allow frequent users to remain logged for a period of several days 
- ​      Add functionality to allow users to give star ratings and a short comment about the recipes they have used 

- ​     Add a BuyOnline option to the ingredients section for users that will earn commission for the site- owner .
  ​               It is possible to earn commission from online supermarkets such as Tesco, Ocado and Sainsbury. The option to click and collect could be added to the recipe ingredients section so that missing ingredients for a recipe can be added to an online order that goes to the supermarket 

-  Advertise and sell gift items such as hampers , items can be drop shipped from Amazon and commission earned as an Amazon associate.
- Advertise and sell kitchen tools and aprons and mugs with the brand logo, for site owner commissions.
- Adsense  ads can also earn commission for the site- owner.  Sections can be assigned within the site and relevant items will be automatically displayed to users. 
-  **Live Chat** so that users can ask questions and get them answered without delay
- **Remarketing pixels** so that the company can remind the visitor that they visited the site 
- Connect to the spoontacular.com API to allow users to search very large database of recipes and get nutrition data about recipes
- Add Twitter and Facebook widgets to each recipe so that users can like and share recipes immediately
- Connect the favourite button on the recipes so that  the Home Page displays those recipes that are popular
- Build out the admin dashboard to show how many recipes are currently on site and which are most viewed
- Build out the user's profile page showing the recipes they have added with likes, shares and favourites, their account details ( username etc)
- Add a print or email option to the add recipe section so the user can easily print or  share the recipe



## Defensive Design

The following measures were used in the SnixSnax website to  anticipate user error  and minimise the consequences to provide a better user experience on the site, by assisting the user to successful outcomes in the site activities :



**Login and Registration**

<u>Blank field submission</u>

Submission of the login or signup form with a blank field  triggers an error message to the user 
Validation (supplied by Materializecss.com) is indicated to the user when filling input fields by use of a red ( warning ) or green (success) line  

<u>Quality of information submission</u>:

Character type  is controlled for each input field -- only numbers between 0-9 and alphabetical characters are accepted 
the user is informed with  tooltip if unacceptable entries are made. 

Character quantity is controlled for input fields  (5-15 characters)   users cannot enter a one letter username or password. 

<u>Flash Messages</u>:
Successful submission of registration or login triggers a message to the user 
Incorrect entry of password or username triggers a user message without specifying which case
Attempting to use a username that is already in use triggers a similar message 

**Adding and Editing a recipe** 

Submission of the add recipe or edit recipe form with a blank field  triggers an error message to the user 
Validation is indicated to the user when filling input fields by use of a red ( warning ) or green colored line for the input 

<u>Character Type </u>:  is controlled for each input field -- only numbers between 0-9 and alphabetical characters are accepted 
the user is informed with  tooltip if unacceptable entries are made. 

<u>Character Quantity</u> : is controlled for input fields  (5-200 characters)   users cannot enter a recipe that is excessively long.

<u>Cancel action</u>    The edit recipe form has both a  cancel and edit button, in case the user changes their mind.

<u>Buttons</u>: are clearly marked, only one option on add recipe form  to submit 
2 buttons on edit recipe form user can choose to continue with edit or cancel

<u>Flash Message</u>  Users receive a flash message to confirm that their edit was successful and that their recipe was added. 


**Deleting a recipe**

<u>Accidental deletion of a recipe</u> of a recipe by a user 
by a user is avoided by the use of a modal triggered when the user clicks the delete button
User receives a warning that the deletion cannot be undone and asked whether they wish to proceed 
The user can cancel the deletion or proceed 
<u>Flash message</u>  the user is notified with a flash  message when the deletion is confirmed

**Future defensive design to implement** 
Admin login is currently based on username this is not ideal  
A better solution is to adjust admin login to a  key:value pair in users section
This allows for more than one admin login on the team and is more secure.

Salt and hash additions to the username and passwords are currently basic and for more security they should be improved.  
    

##     Technologies Used

​        CSS

-  The project uses Cascading Style Sheets (*CSS*) as a simple mechanism for adding style (e.g., fonts, colors, spacing) to the web documents 

​       HTML 

- The project uses Hypertext Markup Language (**HTML**) which is the standard markup language for documents designed to be displayed in a web browser.

​       [Heroku](https://www.heroku.com/)

- The project uses Heroku to deploy the site and to build, run, and operate applications entirely in the cloud.     

​       [Python + Flask](https://flask.palletsprojects.com/en/1.1.x/) 

-  The project uses **Flask** as a lightweight WSGI  ( *Web Server Gateway Interface*) web application framework . Flask includes  Werkzeug and the powerful Jinja templating language and is  one of the most popular *Python* web application frameworks

​       [MongoDB](https://www.mongodb.com/)

- the project uses  MongoDB to store the data required for the project. MongoDB is a noSQL database which stores data in JSON format.

​       [Materializecss](https://materializecss.com/) 

- 

    the project uses MaterializeCSS framework as a source of easy to use elements to  simplify the development process 

    

    [JQuery](https://jquery.com)

    - The project uses **JQuery** to simplify DOM manipulation.


  ### **Testing**

 [Testing](/TESTING.md)   

   
  
    
 - ## Security

  ####  Authentication

  Flask uses Werkzeug for security features and the SnixSnax site makes use of the the standard built – in methods provided to secure users' passwords and username details: 
   generate_password_hash  and check_password_hash 

   Hashing passwords converts a user's pw from plain text into another string which is one-way and practically impossible to reverse and for additional security it will then salt that string with random data. 

  This provides basic but robust security to protect a users registration information

   **Authentication**

  <u>Registration</u> Before the data the user types into the registration is added to the database it is checked to make sure that it does not already exist in the database 
  If it does not exist then it is hashed 

  <u>Login</u>

  Users are authenticated on the basis of their registered username and password 

  **Authorization**

​          <u>Nav bar links</u> are conditional on the user state ( all users, session users or admin )
​          Different sections of the website therefore have access protection   

​         This is 
​                   to give those users that have signed up and are logged in  (session users ) a level of exclusivity not available to all users
​                   to encourage users to register  for the site.  
​                  to provide more site security in the case of admin ( only admin are allowed to edit, add or delete categories)

​         **All  Users**  have access to signup, login logout and home menu links 
​         **Session users** can access home, logout, add a recipe and recipe box link
​         **Admin** users can access home, manage categories, add recipe, logout   

<u>  Recipe Buttons</u> 

​       Edit and delete buttons are only displayed to the author of the recipe 


​    



### **Bugs /Problems during project development**** 

In file app.py Line 64 there is a linting error  that will not go away 
Linting errors exist on each template because the doctype is missing, this is because the jinja formatting cannot be read correctly. 
The doctype for each template is introduced to the templates from base.html  

Originally I used a delete confirm dropdown from the browser as part of the defensive design against accidental user deletion.
On my mentor's suggestion I replaced this with the materialize modal instead, to ensure that the functionality was not browser dependent. 

I had a problem on add_recipe.html template with the card-reveal action. The action was originally working but when I added the if statement
for the session user to the card ,the card-reveal action stopped working . This was resolved with help from Tim the tutor who helped me to rearrange
the code so that the modal was inside the statement but the card-reveal section outside. 

Problems with the hero-image. The image disappeared completely when I tried to add a media query and showed on dev tools that there was an error to do with the linear gradient css.
 This was resolved by adding in the webkits for the different browser types.
 
On dev tools the image looks correct for the mobile version but in real life on an i-phone the image is skewed. 
Despite many efforts to correct this using CSS I still can't get the image to show correctly on the mobile version

Problems with media queries  I planned to adjust the size of the text and search bar in the mobile version using media queries but because it seemed to cause problems with the main image, I rearranged the text and the search and reset buttons instead. 
   





## Deployment

SnixSnax Recipe Club app used  [Heroku.com](www.heroku.com) for deployment from the development version in GitHub 
Before deploying the app some new files must be set up 

- a requirements.text file      use the command pip3 freeze --local > requirements.txt file 
- a Procfile so that Heroku knows what to run and how  use the command  echo web: python app.py >Procfile ( delete empty line at bottom of file )

Now on Heroku.com  the new app was named and the country region selected. 
The automatic deployment option on Heroku was used as follows :

1. The github repository was named and Heroku authorized

2. Go to  Heroku settings, and then to Reveal config vars
![](https://res.cloudinary.com/mr19331/image/upload/v1608021119/Deploying-a-Flask-App-on-Heroku-Config_vars_tmuav2.png)

3. Enter the  IP, PORT , SECRET_KEY, MONGO_URI and MONGO_DBNAME with values  so that Heroku has access to them.
 (this is necessary because these variables are hidden in our code and Heroku has to be able to read them) 

4.Click "Save Changes"

5. Ensure that all files including Procfile and requirements.txt  are and  all code pushed to the master branch. Then on Heroku, go to the Deploy tab.

6. Choose the repository that contains the app and then hit connect.to git so  the development version is up to date When all updates to GitHub are complete simply click "automatic deployment "

 Automatic deployment can be enabled to have changes to the Github master be displayed on Heroku as they are pushed. For this method, there must always be a working master branch.

7. [It]() is also possible to use the manual  deployment option and select "master "

8. Build logs will begin to populate a console on the page. Notice that Heroku looks for a requirements.txt file first

9. When the app is deployed( this will take a few minutes)  it will say "Your app was successfully deployed" and then you can click view to view the app 

![](https://res.cloudinary.com/mr19331/image/upload/v1608021181/successful-Heroku_lf5yvm.png)



    ###Running a Local Version of the App


The following must be installed :

​     IDE  of choice 

​- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) 

- [PIP](https://pip.pypa.io/en/stable/) 
- [Python3](https://www.python.org/doc/) 
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 

Access github repository https://github.com/mr19331/snixsnax 

 Copy the repository --either download the  file**, or clone the repository 

**To download the file** 

On     the GitHub project page, click the download tab to allow you to download the     file.

From     the zip file extract to a folder 

**To clone the repository.**

 Copy  the url      https://github.com/mr19331/snix-snax 

Then  run the following command:

git clone https://github.com/mr19331/snix-snax

**Create a virtual environment**  Use the command python -m .venv venv

[venv](https://docs.python.org/3/library/venv.html#module-venv) will usually install the most recent version of Python available 

**Activate the virtual environment** with:  .venv\Scripts\activate 

**Download requirements** for the project using  pip -r requirements.txt.

**Create the file env.py** and within this file store the following 

SECRET_KEY variable 
 MONGO_URI  to link to your own mongodb database :

**Connect to Mongodb** the database must be named recipe_manager with 3 collections users, recipes and categories 

**To run the app** use command   pyhon3 app.py

 **View the app** by clicking on the browser button that is supplied after typing     pyhon3 app.py 



## Credits

### Content

Code snippets 

 Image gallery on home page from [codepen.io](https://codepen.io/geo555/pen/ZoOWQM) 


### Media
  **Recipe Images** 

- Frozen grapes from [veganheaven.org](https://veganheaven.org/all-recipes/frozen-grapes-the-best-snack-ever/)

- Savoury (cheese & Bacon rolls ) from [kidspot.com.au](https://www.kidspot.com.au/kitchen/recipes/cheese-bacon-rolls/wm3gguui)

- Savoury (veggie chips ) from [kidspot.com.au](https://www.kidspot.com.au/kitchen/recipes/healthy-vegetable-chips-recipe/20ywthc8)

- Savoury ( roasted chickpeas) from [kidspot.com.au](https://www.kidspot.com.au/kitchen/recipes/healthy-roasted-chickpeas/ny7b8cv9)

- Sweet ( bliss balls)from [kidspot.com.au](https://www.kidspot.com.au/kitchen/galleries/kid-friendly-bliss-ball-recipes-lunch-box-treat/ycfgsyzw?r=lunchbox&h=lunchbox)

- Sweet ( apple chips ) from [kidspot.com.au](https://www.kidspot.com.au/kitchen/recipes/homemade-apple-chips/qfsm60l0)

- Sweet ( strawberry rollups) from [kidspot.com.au](https://www.kidspot.com.au/kitchen/recipes/strawberry-roll-ups-sugar-free-recipe/59isss1z)

-Savoury (kale chips)

- Kids 

  

  **Video section on home page**

- cheddar star biscuits from [kidspot.com.au](https://youtu.be/rTkol3a8QXE)

- lemon yoghurt cupcakes from [kidspot.com.au](https://youtu.be/1UvM3htSxME) 

- muesli bars from [kidspot.com.au](https://youtu.be/SQrYOK_RVkc) 

​      Image on About.html page**
​     By Brooke Cagle on [Unsplash](https://unsplash.com/@brookecagle?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) 

### Acknowledgements

- The inspiration for this project  was  from [Delish.com](www.delish.com) and from [All Recipes](www.allrecipes.co.uk) and from [KIdspot.com.au]( KIdspot.com.au)
- Privacy Policy was generated from [Free Privacy Policy](https://www.freeprivacypolicy.com/free-privacy-policy-generator/)
- Adding the functools import and wraps for securing login was aided by  [Protecting Endpoints in Flask apps] (https://blog.tecladocode.com/protecting-endpoints-in-flask-apps-by-requiring-login/)
<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>




