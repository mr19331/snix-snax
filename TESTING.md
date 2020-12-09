# Testing



In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

## Code Testing    

 the following sites were used to validate the code used: 

HTML using [HTML validator](https://validator.w3.org/)

CSS using [jigsaw](https://jigsaw.w3.org/css-validator/) 

JavaScript using [JavaScript Validator](https://jshint.com/) 

Python using [Python Validator](http://pep8online.com/) 

[Developer Tools Lighthouse](https://developers.google.com/web/tools/lighthouse) 



## Manual Testing 

![Links-Testing](C:\Users\Maria\Documents\CodInstitute\MS3\Links-Testing.png)



------

![Button-Testing2](C:\Users\Maria\Documents\CodInstitute\MS3\Button-Testing2.png)



------



![Form-Testing1](C:\Users\Maria\Documents\CodInstitute\MS3\Form-Testing1.png)



![Form-testing2](C:\Users\Maria\Documents\CodInstitute\MS3\Form-testing2.png)

![Form-test3](C:\Users\Maria\Documents\CodInstitute\MS3\Form-test3.png)





### **User Story Testing**

.1.              **As a new /first time  site user** 

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



#### **Possible Actions for this user:**

User can see immediately from  the hero image and text  what the site offers .
A sign up or register link is clearly indicated on the hero image and in the main navbar and side bar.

This user can view  the home page and find recipes for snacks without signing up or logging in:

- ​        the search bar in the centre of the browser view  for  searching for  recipe(s)- accessed with one click 
- ​        if no recipe results from the search - user receives a flash message "sorry no results for this search "
- ​        the category section  on the home page for searching recipe categories - accessed with  image click 
- ​        the "new recipe" section uploaded by club members - accessed with  image click

This user can view how- to videos and click on  shopping adverts to purchase goods- one click access 
This user can access the social media links on the site footer to get more information 
User can view privacy policy, contact us and about us pages to get information on the site owners 

 

2. **As a returning visitor/user to the site:**
   
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
   
   

**Possible Actions for this User :**
User can search for recipes on the home page 
using the search bar 
or by category name 
or by clicking "new recipes"

User can  register
from clearly displayed links in  main navbar, side navbar, hero image on home page or in the footer 

Registration or Login requires only  2 fields  and click submit button
Attempting to submit either form with an empty field returns the message " please fill in this field" 
On successful registration the user is transferred  to their profile page and receives a confirmation message to say "Welcome username" 
Logout is clearly displayed in the main navbar 

Users Recipe Box is displayed with all recipes listed 
The name and  category  of recipe is shown with an image

User can add a recipe or edit their own recipes
Link to the  "Add Recipe" form is displayed in the main menu
Input fields on the Add Recipe or Edit Recipe forms are separate and labelled and have an icon for clarity of purpose 
User input is visibly validated with a green line for success and red for error
User input is controlled by character number and alphanumeric type
 Blank fields on Add Recipe or Edit Recipe  forms trigger a tool tip to alert the user

Deleting a recipe triggers a warning and the user must confirm to complete action successfully  

Editing and delete buttons on a recipe are displayed only to the owner of the recipe  

 Session user may edit  or delete their recipe if they choose by clicking clearly labelled buttons on the recipe card 

Flash messages are displayed on completion of successful activities   Login, Signup, Add recipe, Edit recipe and delete recipe

Privacy Policy is available as a link in the footer 
About Us page and Contact Us page available as links in the footer 
Social Media links are located in the footer section 








|      |      |      |      |
| :--- | :--: | ---- | ---- |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |
|      |      |      |      |






For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

**Cross browser testing**  browsers and screen sizes. 