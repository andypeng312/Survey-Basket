# README
## Description of Project
This is a group project made by Andy Peng and Kechun (Coco) Mao as their final
project for the course 15-237 Special Topic: Cross-Platform Mobile Web Apps.

The project is a site for creating, distributing, and taking surveys. The site
has tools to create your own survey and generate a unique URL for distribution,
it allows users to sign up to create and take surveys and has a credit system
to incentivize survey-taking, and it allows you to view survey results as a pie
chart or in tabular form.

On the backend, user data and surveys are stored on a MongoDB database running
on a Node.js server using the mongoose package. The other Node.js packages used
are Express as a web application framework and Passport for user
authentication.

On the frontend, jQuery and Underscore.js are used to load surveys and user
data onto a fully responsive, mobile-friendly UI created with Bootstrap.

A version of the site is also hosted at http://surveybasket.heroku.com/ and an
Android app of the site was created using PhoneGap and included in the 
repository as `Surveybasket.apk`

## Contents
* **`screenshots`**- contains images that show each page a user would encounter
throughout the site on both a mobile browser and a desktop browser
* **`Surveybasket`**- contains the files for the project; to run the project:
1. Open a terminal in the `Surveybasket` directory
2. Run the command "./mongodb-osx-x86_64-2.2.2/bin/mongod --dbpath data/db/" to
   start the mongodb server
3. Open another terminal in the `SurveyBasket` directory
4. Run the command "node server.js" to start the node server
5. Open a browser and load the URL http://localhost:3000/
* **`Surveybasket.apk`**- an android mobile app version of the site created with
PhoneGap
---
**Technologies used:** HTML, CSS, JavaScript, jQuery, Node.js, MongoDB, Express, 
Underscore.js, Bootstrap, responsive web design, AJAX, client-side caching  
**Estimated Lines of Code:** 3400

![](/screenshots/desktop/screenshot1.png)  
Log-in page

![](/screenshots/mobile/screenshot1.png)  
Mobile version of the log-in page

![](/screenshots/desktop/screenshot9.png)  
Main page

![](/screenshots/desktop/screenshot5.png)  
Creating a survey

![](/screenshots/desktop/screenshot12.png)  
Viewing survey results

