# Movie Recommendations Fe Assignment
This repository contains an assignment for our summer interns'19 candidates.

## Description 
In this assignment you are required to download the code in this repository 
and update it "as you wish" adding your piece of mind. 

## Ideation 
This code is for the front-end we will be using with our movie recommendations 
engine, which is currently work in progress. Simply through this game application, 
users can visit the website (for which this is the front-end), where they can 
rate several movies and subscribe to our service. In return at the end of each 
month we will send them recommended movies that we think they would like the 
most - based on the ratings they have provided previously. There are of course 
lots of other features that we don't tell here ;) we'll keep it a surprise when 
they are implemented. 

![alt text](img.png)

## After Modifications
![alt text](capture1.png)
<br>
![alt text](capture2.png)
<br>
![alt text](capture2.png)


## Features supported by the front end 
As can be seen from the image below the features included are: 
 - Header Section Controls
   - Visitor will enter his email address. In return our WebServer will send an authentication token to the email address provided
   - Visitor will verify their email address by entering the received authentication token 
   - Visitor can subscribe/unsubscribe to our service (same button, which will change based on the user status, i.e. subscribed or not)
   *this replaced with just subscribe button through it the website request from user to complete a login form if he/she didn't login before*
   
 - Movies Section Controls 
   - Visitor can search for a movie (right search panel)
   - Visitor can filter the movies by year or type (left drop down lists)*this replaced with Dropdown Menu navbar*
   - Visitor can get the next batch of movies.*that button exists in the end of main content page*.
   - For each movie
     - Visitor can provide a rating 
     - Visitor can ask us to provide him "his learned rating" *the name of button replaced with review*.

