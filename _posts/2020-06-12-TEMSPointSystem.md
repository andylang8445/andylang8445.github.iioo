---
title:  "TEMS Academy Point System Project"
date:   2020-06-10 00:06:00
categories:
- Programming
- 2020 Project
- Finished Project
- Volunteering
tags:
- TEMS Academy
- Web Development
- HTML
- CSS
- Javascript
- NodeJS
- express
- PHP
- AWS
- Google Cloud Platform
---

<h1>Canada TEMS Academy Point System</h1>
Web Page Development

# Preview
Real-time Web Page that can keep track of individual students' points for the reward system during COVID-19 situation.

## Requirements
* Students should be able to access their current point status with some details and their current ranking in the system
* All data should be up-to-date at all times
* Teachers(Tutors) should be able to give or subtract the points as needed, but students' should not be able to access this function

## Platform used in this project
* AWS(Amazon Web Services)
    * Web Server (Apache) server hosting
    * NodeJS Server
* Google Cloud Platform
    * SQL Server
    * Bucket(image) Server

# Planning

## Student Side
1. The public ip address directly brings the client to the point ranking board
2. When the client is recieveing the point data from the server, the datas are already sorted by point(decreasing order)
3. Users are able to change the sorting options without refreshing the page.
4. When the user reloads the page, the server sends the current data at the moment.
<figure>
  <img src = "https://i.imgur.com/VGd1Q7Z.png"/>
  <figcaption><center>The screenshot of main console</center></figcaption>
</figure>


## Teacher side
1. There is the login tab for the tutors on the top menu bar.
2. When login action happens, PHP goes through the authorization process; which is basicly checking the id and passward.
    * id has to be unique to prevent the errors that might occure, but passward does not have to be unique
3. When the authorization process has the error, the wabpage redirects to the error page to indicate the details of the error message.
4. When the authorization goes through and successfully finished the login process, the webpage redirects to the tutor's section.
5. In tutor's section, there is a selecting tool where the tutor can choose a student to change the point.
    * When the tutor's section is initially being loaded, a invisible table of students' name and current poing status gets loaded at the same time.
6. There are buttons that teachers can use to give poings the take points away according to the point rules. They can also maiually input the changed point for individual students at the page
    * There is a line of text that indicates the current status of the NodeJS Server at retries to connect to server when it is not being connected
    * There is a big red button for resetting the database when the teachers need to do so.
7. When the tutor finishes updating the poing for the student, they should press Send button to update the database.
<figure>
  <img src = "https://i.imgur.com/qjmjo4h.png"/>
  <figcaption><center>The screenshot of tutor's section</center></figcaption>
</figure>

## Server Side
### Webserver
Used with Apache and PHP
* All webpages are based on HTML, Javascript, CSS, and PHP
* All datas from SQL server are loaded with the HTML File by PHP
* Tutor's page is connected to NodeJS server with SocketIO adn express
* Server that interacts with users directly
* Runs on CentOS and AWS LightSail
### NodeJS Server
The server to update the database
* Being used for tutor's page to update students' points with input
* Runs on AWS Lightsail NodeJS Server
* Used forever to keep the service running on the background and automatically restarts the program when the server has been rebooted
### SQL Server
Server used for storing up-to-date student point status and storing tutors' login data
* Initially worked on Google Cloud Platform
    - Google Cloud Platfor has better UI for database management, but difficult to change data on the website (had to use third-party program to access the server and change the data)
* Have moved to AWS SQL server on Lightsail because of the cost issue
    - AWS SQL server has difficult UI for a entry-level users, but can access the server directly from the web page(Still easier to use other program. I used Sequel Pro)
### Image server