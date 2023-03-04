# Q-Hub

Q-Hub is a simple question forum that allows users to ask others about any types of questions. This efficient application provides a platform where individuals can have discussions about any topic. After creating an account, the user is able to post their specific questions, answer other's questions, and view questions that they have already asked.

## Project Description

To build this application, four different HTML pages (Sign Up, Login, Homepage, Profile) were created using the templating engine Handlebars. The structure and styling of the pages employed the Bootstrap CSS framework. Basic functionality such as event listeners were incorporated with plain JavaScript.

- Sign Up: The user is first prompted to the Sign Up page where they can generate a new account with a User Name, Email, and password.
- Login: To login, the user needs to input their email and password.
- Profile: After login, the user will land on the profile page where they can view all questions asked. This is the result of the GET route that retrieves the user's data.
- Home Page: On the home page, the user can click on 'New Post' to post a new question, with its own title. Through the POST route, other users can view the questions being asked.



## Technologies Used

- Bootstrap: CSS framework
- Handlebars.js: rendering of HTML pages
- Node.js & Express.js: create RESTFUL APIs
- MySQL & Sequelize ORM: create databases
- Cookies: authentification
- Heroku: deployment of live site

## Demo of Deployed Site
- https://drive.google.com/file/d/1vRUeOc4dyBONuOknOsy0LNTvfyq_urVl/view?usp=sharing

## Project URLs
- Github: https://github.com/nguyensang0323/Question-Hub
- Heroku: https://damp-plains-26918.herokuapp.com/
