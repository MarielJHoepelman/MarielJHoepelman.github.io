---
layout: post
title:      "JavaScript project: Cutie Cards!"
date:       2021-01-22 22:57:07 +0000
permalink:  javascript_project_cutie_cards
---


For the V8 curriculum’s fourth project, I created a Model View Controller Rails application called [Cutie Cards](http://github.com/MarielJHoepelman/cutie-cards). [Cutie Cards](http://github.com/MarielJHoepelman/cutie-cards) is a memory game designed for children (or anyone that is into cute stuff). A memory game is a card game in which all of the cards are face down and two cards are flipped over each turn until all cards are matched with their corresponding pair. After entering a username, the faces of the cards are displayed for a few seconds, then all the cards turn face down. The user proceeds to play by turning over pairs of cards to match their kind by clicking on the back of the card. The user has a limited amount of moves to complete the game. Each move equals two clicks. When two matching cards are clicked consecutively, the remaining cards get flipped. A round is won when all the cards have been matched before running out of available moves. 

[Cutie Cards](http://github.com/MarielJHoepelman/cutie-cards) is a single page application. The frontend is built with HTML, CSS and Javascript and the backend with Ruby on Rails. The backend consists of two models, User, in charge of handling user registration and login, and Score which saves and tabulates the user's best scores. The models store and validate data and the relationships between them. The application has three endpoints: users/create: to create users in the database, scores/create: to save scores for the users, and scores/index: to show a list of the best scores.  The application is configured so it doesn’t persist invalid data such as empty inputs and duplicates. For this, models implement the Active Record validation feature presence which verifies empty data is not saved in the database. Failed validations display error messages to the users in the frontend. 

Communication between a user and the backend is handled asynchronously and uses JSON as the data interchange format. The application uses ES6 syntax when appropriate and object oriented programming to encapsulate functionality and behavior, and uses RESTful conventions, specifically GET and POST, to handle the creation and display of new users and scores.

