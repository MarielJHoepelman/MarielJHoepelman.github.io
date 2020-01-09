---
layout: post
title:      "Sinatra project: Wishable!"
date:       2020-01-09 02:59:16 +0000
permalink:  sinatra_project_wishable
---


For the curriculum's second project, I created a Model View Controller Sinatra application called [Wishable](https://github.com/MarielJHoepelman/flatiron-sinatra-portfolio-project). Wishable is a wishes tracker that allows a user to create Wish Lists and see other users' lists. Wishable consists of three models: User, WishList and Wish. The models store and validates user data and the relationships between user, wish lists and wishes. 
Users can safely log in and log out. They can create, edit and delete their own lists and wishes but not other users lists. 
The application is configured so it doesn't persist invalid data such as bad formatted emails or urls or duplicate data. For this, models implement the Active Record validation features uniqueness and presence which verify empty data is not saved in the database. Failed validations display error messages to the users and redirect to the appropriate route.
Wishable was a challenging yet rewarding project. Developing this project allowed me to think more as a developer, looking constantly for ways to make my code more efficient and readable.
It allowed me to better understand the relationship between the models, views and controllers. 


