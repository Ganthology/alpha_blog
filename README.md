# Alpha Blog
This is my first tutorial project for the Complete Ruby on Rails Developer course on Udemy. This is the first website I build using Ruby on Rails and deployed to Heroku.

[Link to the project](https://ganthology-alpha-blog.herokuapp.com/)

## What I learned from this project
- Understand the relationship of Model-View-Controller(MVC) in rails, how they associate with each another. 
- How routing works for rails webpages
- Add tables and columns to database using migration files.
- Using a Form helper to build the form for user. 
- Use ```bcrypt``` gem to encrypt user passwords, ```has_secure_password```
- Whitelisting and validates form inputs.
- Track user logged in using ```Sessions Controller```.
- Add pagination using ```will_paginate``` gem.
- Use partial for repeating erb templates.
- Apply one-to-many association to Articles and Users.
- Add admin functionality by adding an admin column to Users db.
- Use ```Bootstrap``` to style the webpages.
- Use ```flash[:notice]``` and ```flash[:alert]``` to display messages.
- Use ```Application Controller``` to define methods used across the Controllers.
- Use ```Application Helper``` for methods used in the views and erb templates.
- Use ```Test Helper``` to defind methods used across the Tests.
- Test Driven Development, learned the syntax for test scripts and how to generate one using ```rails generate test_unit:scaffold```.
- Understand what is Functional/Controller Test and Integration Test.
- Use ```git checkout -b``` to make new feature branch in git.

## Dependencies
I use Ruby on Rails 6, Ruby 2.7.2, Bootstrap 4.6 in this project. The gems I added are ```bcrypt``` and ```pg``` for postgresql in Heroku.