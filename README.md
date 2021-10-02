# **Family Recipes**
[View a live version of Family Recipes here]()
This is the main website for *Family Recipes*. This website will allow customers to store their precious family recipes, so they are never lost again. 
![Family Recipes on mobile, ipad, ipad pro and desk top.](images/tohkresdes.png) "The Other Hong Kong on multiple displays"
![Family Reecipes on many types of devices and showing each page.](images/ohkresdes2.png) "The Other Hong Kong on multiple displays and showing different pages."
## Table of Contents
### [User Experience](#user-experience-(ux))
#### [User Stories](#user-stories)
* [First Time Visitor Goals](#first-time-visitor-goals)
* [Returning Visitor Goals](#returning-visitor-goals)
* [Frequent Visitor Goals](#frequent-visitor-goals)




### [Design](#design)

* [Color Scheme](#color-scheme)
* [Typography](#typography)
* [Imagery](#imagery)
* [Features](#features)
* [Wireframes](#wireframes)
### [Technologies Used](#technologies-used)
* [Languages Used](#languages-used)
* [Frameworks  Libraries and Programs Used](#frameworks-libraries-and-programs-used)
### [Deployment](#delpoyment)
* [GitHub](#github)
* [Cloning to Local Device](#cloning-of-repository-to-a-local-device)
* [Setting up a google maps javascript API](#Setting-up-a-google-maps-javascript-API)

### [Testing](#testing)
### [User Stories] (#)
[Photo story for first time user](#photo-story-for-first-time-user)
[Bugs](#bugs)
- [Gallery](#gallery)
- [Navbar](#navbar)
- [form](#form)
- [Javascript for Maps](#javascript-for-maps)
- [Javascript for mail](#javascript-for-mail)
### [Acknowledgements](#acknowledgements)
* [Media](#media)
* [Individuals](#individuals)


## User Experience (UX)


 
 1. First Time Visitor Goals
    a. A first time user will be able to register their account.This will then allow the user to add recipes to the database. These recipes can be either private or public. Those old fanily recipes can remain precious secrets. We all know that grandma may not want everyone to know what goes into her delicious lasangne. For other home cooks they may want other families to create their own memories with their recipes. 
      
        
    b. The colours are classic and conjure the image of plain white paper and black ink. The cursive style font helps suggesting old fashioned hand writing. 

    The Navbar in bright white with text in black like the elegant scribblings on an old notebook. The menu goes from the center to the right and on mobile devices comes in the form of bars icon with a drop down menu on the right. 

        
    c. Below the navbar is a illustration of cooking utensils with a  card atop explaining the reason for the database and prompting the user to register by hitting the registration button. Both registration and log in can also be accessed via 

    d. The Explore button in the navbar leads the user to main interactive component of the site. My clicking hikes, markers for five different hikes in hong kong will appear with details regarding difficulty and length of hike. 

    e. Contact will allow the user to get info to any further details about locally organised group hikes in and around Hong Kong. 

  
 2. Returning Visitor Goals 
     A returning visitor will be able to log in easily and continue to update their family cookbook. They can add and edit recipes as they go. Compiling as many recipes as they like. 
    
3. Frequent User Goals 
    A frequest User will see the benefits of having their family recipes on one database. They can check the old family recipes and share it with other family members and friends. They user may also want to double check how much flour goes into that victoria sponge. This site is there to remind the user. 
           

# Design 
  ## Color Scheme  
  * Three main colors where chosen. These colours were inspired by the image of the sun setting over Hong Kong City. The main colour is that of pink salmon
     Colors are pinksalmon like a sunset and darkslate gray to represent the concrete jungle below.
 ## Typography 
    
  * Font used is Satisfy and cursive. I wanted something relaxed and flowing. 
 ## Imagery
  * Images used were from Unsplash and of particilar hiking locations in Hong Kong. 
  
## Features
* Responsive on all devices and have interactive elements for bookings. Icons that link to further social media updates.

## Wireframes

* Wireframe for the whole project. [View](assets/wireframes/tohk2021.pdf)


![Homepage wireframe.](images/tohk2021.png) "Home page wireframe "
"

# Technologies Used 
## Languages Used 
* HTML
* CSS
* Jquery
* Python
## Frameworks Libraries and Programs Used 
1. [Materializecss](https://materializecss.com/)
  
    Materialize CSS

3. [MongoDB](https://account.mongodb.com/account/login?signedOut=true)

    Database usedto store recipes and site info.  
4. [Google Fonts](https://fonts.google.com/specimen/Pacifico?preview.text=Pacifico&preview.text_type=custom&query=Pacifico)
5. [Fontawesome](https://fontawesome.com/)
    Fontawesome was used for to get icons for utensils and aa cocktail on the feast page. 
6. [Gitpod](https://gitpod.io/workspaces/)
    Used gitpod to work on my repositories. 
7. [Github](https://github.com/MichelleCoffey/A_Moveable_Feast_Shanghai/tree/1a91746d21707106faef91c699500aff9414e097)
     GitHub is hosting my repositories. 
8. JQuery: 
    * Is used by Bootstrap.

9. [Balsamiq](https://balsamiq.com/)
    * Balsamiq was used to design and organise my WireFrames. 
10. [TinyPNG](https://tinypng.com/)
     * Tinypng for fomatting images, so they loaded faster.
11. [Unsplash](https://unsplash.com/)
    * Upsplash was used to access some stock images to add to the site and in particular the hero image and background image. 
12. [Shutterstock](https://www.shutterstock.com/)
    * Shutterstock was used for the heroimage. 
13. [BBC FOOD](https://www.bbc.co.uk/food)
    * Recipes.


## Deployment 
### Github

### Requirements 
  1. Github account
  2. Gitpod account
  3. Mongo db account
  4. Flask 
  5. heroku account


#### The repository is hosted on github and I have therefore used github pages to deploy the site. 
  1. On Github, go to your site's repository.
  2. Under your repository name, click settings and scroll down to Github pages. 
  3. Under the "Github pages:", use the None or Branch drop-down menu and select a publishing source. For a Moveable Feast, the master was selected, root and both actions were saved using the save button. A theme or custom domain were not chosen at this time. 
  4. After saving the actions. Next click the active link on the repository page on Github. Full deployment may take a minute or two, so refresh the page and be patient. 
  
#### Cloning of Repository to a local device.
  1. On GitHub, again go to the main page of the repository. 
  2. Above the ist of files, click Code. 
  3. To clone the repository using HTTPS, under "Clone with HTTPS", click. 
     To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click . 
     To clone a repository using GitHub CLI, click Use GitHub CLI, then click .
  4. Open Terminal 
  5. Change the current working directory to the location where you want the cloned directory. 
  6. TYpe git clone, and then paste the URL you copied eariler. 
  7. Press Enter to create your local clone. 

#### Working with Gitpod
  1. Install all of the requirements. In the termianl window type pip3 install -r requirements.txt.
  2. Create a databae in Mongo db. 
      * Sign up if needed. 
      * Create and cluster and a database. 
      * Create cluster for family_recipes and in it create a further three collections: user, categories, and recipes. Add string values. 
  3. Create the variables. 
    * Create a gitignore file and create and env.py file. 
    * Add environment variables. 

                  Import os
              os.environ.setdefault("IP", "Added by developer")
              os.environ.setdefault("PORT", "Added by developer")
              os.environ.setdefault("SECRET_KEY", "Added by developer")
              os.environ.setdefault("MONGO_URI", "Added by developer")
              os.environ.setdefault("MONGO_DBNAME", "Added by developer")
          
    #### Heroku Deployment

    1. In terminal window type pip3 freeze -- local > requirements.txt.
       * Then write python app.py > Procfile. This file is needed by Heroku. 
    2. Create a Heroku account. 
    3. Choose deployment method via Github. Search your github using the name of your repository name. 
       *  Click on the repository to connect with it. 
       * Add Config Vars in settings. 
       * ENTER IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME.
    4. Push requirements.txt and Profile from gitpod. 
    5. Use Automatic Deployment on Heroku and Deploy Branch

                            



  












## Testing 

### Photo story for first time user

### User Stories

 ![The Other Hong Kong homepage on mobile, ipad, ipad pro and desk top.](images/tohkresdes.png) "The Other Hong Kong on multiple displays"
 
  ![The Other Hong Kong feast page on mobile, ipad, ipad pro and desktop.](images/find.png) "Feast page on multiple devices. "

  The home page greets you with a sunset over Hong Kong and a challenge to climb the mountains you usually see on the way to work. 

  
  As the user scrolls dowm, the will find buttons the link to markers and infowindows on the map. The infowindows will introduce the more exciting part of Hong Kong, some history about the locations and the vistas you can expect to view. 


  ![The Other Hong Kong contact page on mobile, ipad, ipad pro and desktop.](images/contactpage.png) "Contact page on multiple devices. "

  The user will have the oppourtunity to register there interest in hikes. 

![successful validation confirmation](images/homevalidator.png) "Home Page HTML success."

W3C CSS Validator Services was used to validate CSS.

![successful validation confirmation](images/cssvalidator.png) "Home Page HTML success."
 * the flexbox that was pinged was actually necassary for the image and remained in the CSS.

![successful validation confirmation](images/mapjsval.png) "Home Page HTML success."

![successful validation confirmation](images/mailjsval.png) "Home Page HTML success."

![Lighthouse Performance 77%, Accessibilty 89%, Best Practices 93%, SEO 100% on desktop](images/lighthouse.png) "Lighthouse score for the websites user efficency."

### Bugs
#### Gallery

1. Images were a little big so I used tinypng to compress them. 
2. I used an hiking icon in the map and I got and figured out how to use this by downloading a small px hiker. 

#### Navbar
* Had a glitch that made the toggler appear at all times. This was remedied by comparing my code and bootstraps code for responsive togglers. I was able to find the error in the html. 
 #### Form 
 * The form pushed left on small devices. I removed the width of 400px, which helped and then targeted the media query on larger devices. 

 #### Javascript for Maps

 * My mentor recommended a youtube tutorial by Sam Codes that help with my ideas and intial coding for markers and infowindows. 

 [Sam Codes](https://www.youtube.com/watch?v=uPhWSyRqQDA)

 * I then needed to link the buttons with the markers and infowindows. This was helped with tutors and with Stackoverflow onclick explanations. This caused an issue when I put function within let markers within the init map function when it needed to go before it.

 * Finally I needed to make sure a window would close when a new one was opened. This was also achieved by looking at another W3schools tutorial. [Stackoverflow](https://stackoverflow.com/questions/2223574/google-maps-auto-close-open-infowindows)

 #### Javascript for Mail
 * My initial mail wouldn't work or was sending it when the page opened, without any input. I then had to add windowonload before the function and this worked. 
## Acknowledgements
### Media
* Code Institute Tutorials for providing a jumping off block. 
 * Slack for being a great source of help with either googling or when other students have provided suggestions to help improve your work. 
 * Code Institute Tutorials. 
 ### Individuals
 * My Mentor, Precious Ijege. 
 * Tutors at Code Institute are great guiding hand.   They do not give you the answer but ask the right questions to lead you down the correct path. It also helps build confidence. 
 * Anne Greaves and Code Institute for a comprehensive guide to writing README.md. The template was taken from the Code Institute Guide to writing README and how to write Markdown.
 * I have also used elements and the template of my first read, such as the table of contents. 
 * Alex Harvey, a guide to writing a table of contents in gitpod. 


#### Code
 As mentioned in bugs. 
 * My mentor recommended a youtube tutorial by Sam Codes that help with my ideas and intial coding for markers and infowindows. 

 [Sam Codes](https://www.youtube.com/watch?v=uPhWSyRqQDA)

 * I then needed to link the buttons with the markers and infowindows. This was helped with tutors and with Stackoverflow onclick explanations. This caused an issue when I put function within let markers within the init map function when it needed to go before it.

 * Finally I needed to make sure a window would close when a new one was opened. This was also achieved by looking at another W3schools tutorial. [Stackoverflow](https://stackoverflow.com/questions/2223574/google-maps-auto-close-open-infowindows)

 #### Javascript for Mail
 * My initial mail wouldn't work or was sending it when the page opened, without any input. I then had to add windowonload before the function and this worked. 