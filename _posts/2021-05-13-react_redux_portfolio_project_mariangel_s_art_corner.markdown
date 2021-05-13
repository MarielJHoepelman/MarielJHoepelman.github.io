---
layout: post
title:      "React/Redux Portfolio Project: Mariangel’s Art Corner"
date:       2021-05-13 21:29:19 +0000
permalink:  react_redux_portfolio_project_mariangel_s_art_corner
---


To be honest, I thought I would never write this blog. Though when I started the program I believed I would make it to the end, at some point when the concepts started to get harder and things went from “Hello World” to Active Record Associations I truly thought I wouldn’t make it to now. 

For this final project, I wanted to create something extra special. Something meaningful to me at a personal level. A project that would make the time, the effort and the anxiety worthy.  So I created an online art portfolio and e-commerce for my daughter Mariangel who helped me during my 3 years journey in Flatiron, not only by babysitting her sister, or taking over for me with the household chores when needed, but also by creating all the graphics and logos for my other projects.


[Mariangel’s Art Corner](https://github.com/MarielJHoepelman/mariangels-art-corner), is a virtual “thank you to my daughter” single page application, composed of 13 containers and 17 components . It has a backend written in Ruby on Rails and a Frontend written in React. The application uses react-router and  RESTful routing navigation that connects the client to the home, art, about, FAQ, shop and contact us views. [Mariangel’s Art Corner](https://github.com/MarielJHoepelman/mariangels-art-corner) uses Redux middleware to respond to and modify state changes and uses asynchronous actions to send and receive data from the server. 

The Rails API handles the data persistence. The backend implements a content management system using the Rails gem [Active Admin](https://github.com/activeadmin/activeadmin) to manage the creation and update of the portfolio content and store products. The creation and authentication of users accounts is handled by [Devise](https://github.com/heartcombo/devise), a flexible open source authentication library that simplifies user management by providing actions that validate and authorize users requests.  The payment processing simulation is handled by Stripe, a payment processing platform with built-in components and customizable forms. 


The application's frontend uses fetch() within the actions to GET and POST data from the Rails API and handles the display of data with minimal manipulation from the client. It uses styled-components to create custom CSS styles with CSS-in-JS.

Working on this project has been exceptionally challenging. It definitely integrated all the concepts I’ve learned so far and forced me to go above and beyond the basic requirements. Going thorugh this process showed me I know more than I give myself credit for, but also that I have much more to learn still.  

![](https://i.imgur.com/TQvMGHum.png) 

![](https://i.imgur.com/Akdxy6Cm.png)  

![](https://i.imgur.com/HZCqUs9m.png)   

![](https://i.imgur.com/vjtp3kem.png)

![](https://i.imgur.com/YRSVFuBm.png)

