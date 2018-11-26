---
layout: post
title:      "BoxOffice CLI Project"
date:       2018-11-26 02:09:37 +0000
permalink:  boxoffice_cli_project
---


After many lessons and labs later, I finally got to do my first project (yay!), a Command Line Interface (CLI) application for scraping content from a website. The project encompases all lessons learnt until now, such as declaring variables, scopes, object instantiation, control flow, instance vs class methods and iterations through objects. Also, this was an opportunity for learning how a gem operates and how to set up a Ruby client application from scratch sing the bundle gem generator.
 
First problem encountered was, what to do? Deciding on what to do for the project was very challenging. There were many options plus the intention to develop a CLI that was different and unique. Later discovered that being different or unique was not necessary because the school is probably not looking for uniqueness but rather seeing whether or not students are capable of applying their knowledge into the creation of the project.
 
After a lot of though there were three options, one: [producthunt.com](https://www.producthunt.com/) hot products list , two: [Amazon best seller books](https://www.amazon.com/best-sellers-books-Amazon/zgbs/books) and three:  [MTA](http://mta.info) app for scraping MTA service status of NYC subways. Why didn’t pick any of these? Part of the development of the project is to test whether or not the pages are scrapable, none of these pages were.The formatting of the data was not standardized, or the content was not displayed on page load, meaning that nokogiri couldn’t access the information. At the same time I was researching for movies go watch over the weekend, and 💡! That’s how [BoxOffice CLI](https://github.com/MarielJHoepelman/box_office) was born. 
 
BoxOfficeCLI is a command-line app that allows users to check a list of movies in the box office. When the CLI is ran,  users see a greeting and are asked to enter a number corresponding to a prompt. The prompts are:  instructions for using the app, movie listing, and exit. When users enter the movie listing choice, they'll see a list of current movies in the box office scraped from: [imdb.com](https://www.imdb.com/chart/boxoffice). From the movie list view, users are given the option to enter a number to see details associated with that specific selection. The classes that support the CLI are: Movie List to get the initial list of movies from the box office, Movie class to hold information of individual movies, Scraper as a nokogiri interface to fetch the data from the IMDB.com, and CLI for user interaction. 


