---
layout: post
title:      "My First Sinatra App"
date:       2020-02-09 14:49:23 -0500
permalink:  my_first_sinatra_app
---


A lot has happened since my last blog post - most significantly I was hired into my first junior engineering role and had to put Flatiron on the back burner for a few months.  I got back on the horse about a month ago, and I have really enjoyed learning Sinatra and building my first basic CRUD app!

My project is a beer reviews app.  It allows visitors to peruse a list of beers, reviews, and styles as well as creating an account, and logging in or out of the app.  When a user is logged in they are able to add new beers to the database, as well as write reviews on any beer listed.  They can edit or even delete their own beer reviews, as well.

Coding this project was intimidating at first - after all, there is no initial project structure provided for us like the lessons usually include.  I had to build out the entire repo, including the folder structure, the gemfile and all of the included gems, the environment, the classes and domain models, and the database schema - all from scratch.

But once I got things rolling, I really enjoyed the process.  I started by getting all of the models planned out, and creating the migrations files to define the database tables and the relations between my models.  From there, I focused on getting the user functionality going.  After all, you can't build user reviews if there are no users and no way to log in!

Once I had the basics of creating a user and logging in, I began building the relevant views and routes for the major models.  For the initial build, I generally focused on one model at a time, (ie beers) and built out all of the necessary RESTful routes and their corresponding views and forms.  Once I had the beers functionality working at a basic level, I moved on to styles and reviews in the same way.

Once the basic structure for all of the models and views was done, it became a very iterative process.  I would test the app extensively by running it locally through a shotgun development server.  This allowed me to test my links and flows, identifying bugs and unintended behavior as I went.  Every time I noticed a bug or something else I didn't like, I would pause and code a fix.  Then I would test again, and commit the change to my git repo.

Overall I would guess I've put about 30 hours of work into building this application.  It may not be pretty, but I'm very happy with the functionality and I learned a lot.  Looking forward to moving on to Rails for my next project and moving towards more complex projects!

You can see a walkthrough of the app's functionality here: https://youtu.be/OHJBM0ITD0s 
