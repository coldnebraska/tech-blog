# tech-blog [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## Project Description
This project is a CMS-style blog site that is similar to a wordpress site and deployed using Heroku. This website follows the MVC paradigm for its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication. I learned how the MVC (Model-View-Controller) paradigm allows for full separation of concerns within the codebase architecture. For the model, this website uses Sequelize as the ORM for handling the structure and logic of the database. For the view, this website implements Handlebars.js as a template engine instead of hardcoding the HTML for each of the webpages. For the controller, this website is using Express.js to take input from the user and interact with the model to create, read, update, or delete data from the database. Then it returns the results and displays it to the user via the template engine. This webapge also implements authentication to access certain features. The authentication uses Express-Sessions and cookies to keep users logged in and authorize them to access all of the features.

## Table of Contents
[Screenshots](#screenshots)  
[Live Application](#liveapplication)  
[Usage](#usage)   
[License](#license)  
[Questions](#questions)  

## Screenshots
![Alt text](/images/homepage.png)
![Alt text](/images/login.png)

## Live Application
https://young-sands-20270-649300120b02.herokuapp.com

## Usage
This website is a typical blog style website. Upon loading, the home screen is displayed showing all of the posts by users. When a post is clicked, it will display that post and any comments that it may have. To leave a comment on the post, the user is required to be logged in. After clicking the login button, the user can either log in using their credentials or click the "sign up instead" button and filling in the required information. After logging in (or signing up), the users dashboard will be displayed. The dashboard is where all of the users' posts are displayed (if any). On the dashoboard, the user can either click on a post of theirs to update or delete it, or they can create a new post.

## License
MIT License

## Questions
Github: https://github.com/coldnebraska  
Email: brush.david99@gmail.com
