---
layout: post
title:      "Rails project: Makeupnizer!"
date:       2020-08-13 20:00:50 +0000
permalink:  rails_project_makeupnizer
---


For the curriculum’s third project, I created a Model View Controller Rails application called [Makeupnizer](http://https://github.com/MarielJHoepelman/rails_portfolio_project). The [Makeupnizer](http://https://github.com/MarielJHoepelman/rails_portfolio_project) app is a makeup tracker that allows a user to keep track of their makeup collections by category. [Makeupnizer](http://https://github.com/MarielJHoepelman/rails_portfolio_project) consists of four models: User, Product, Category and UserProduct. The models store and validate data and the relationships between them. Users can signup and login using their email and password or via the [Google OAuth](https://developers.google.com/identity/protocols/oauth2) API. Once signed up, users can create, edit and delete their collections but not other users colecctions. The application is configured so it doesn’t persist invalid data such as bad formatted emails or duplicate data. For this, models implement the Active Record validation features uniqueness and presence which verify empty data is not saved in the database. Failed validations display error messages to the users and redirect to the appropriate route. Developing this project allowed me to better understand data relationships and the process of normalization of data.
