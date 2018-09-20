# New York Times Article Scraper

## Overview

This web app scrapes the New York Times news site for articles and displays them on the webpage using request and Cheerio (a node.js package). The title, summary, and link to the actual article are provided in separate boxes. When no summary was provided by the New York Times, a default "no summary provided" is displayed instead.

Users have the ability to save articles, visit their saved articles on a separate page, and add/delete notes for each article. These notes and articles are saved in a Mongo Database. 

## Technologies Used

Technologies used include: HTML, CSS, Bootstrap CSS/JS, node and several node packages including express, mongoose, request, and cheerio, and 
Handlebars for the HTML template.

