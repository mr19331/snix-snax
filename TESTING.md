# Testing
.

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
or by category name by clicking the image on the home page 
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

3 **As the website owner/admin user:**

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

** Possible Actions for this User:**

Allowing users to contribute their own recipes will attract users to the site.

Site users will stay on the site longer by adding their own recipes and editing them, viewing new recipes , viewing items for sale, and viewing videos.

Personal information provided  by users is salted and hashed to maintain security.

Users can contact the admin team from company information on the Contact page
 
Login, logout actions are clearly indicated and simple in format

Problems such as blank fields are indicated by red validation line in the input field and a message to indicate errors and success.

Category editing is an admin only section and other users do not have access -- categories can be edited, added or deleted, using button features all of which are clearly marked.

Deletion of a category requires confirmation before the action is completed. 
Actions by admin users receive a success or error message 

Monetization of the site is possible in several different ways
the site can allow other related businesses to advertise or the site owner can advertise related goods and earn commission. 
Commission can also be earned by running a related Youtube channel and advertising . 3    

**Version Testing**

Chrome developer tools --on the Chrome browser was used constantly during development to add styles to conveniently try changes immediately and to check basic layout of the website and to check site responsiveness on different screen sizes

Mozilla developer tools- used particularly to assess the site for accessibility in terms of text visibility ( contrast)

**Display testing**
Accessibility

Used HTML5 semantic elements title, nav, footer, form, header, button, section to clarify elements for screen readers, search engines & developers

Used mozilla developer tools to check readibility of text in terms of contrast

Used alt tags to describe images in case browser can't load and for SEO purposes.

Used simple text font for visibility

**Cross browser testing**  the Snix Snax Recipe Club site was tested on Chrome and Mozilla  for all 3 versions
and on Safari for tablet and iphone versions  