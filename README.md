# User-Authentication-System

- Implemented a custom user authentication system that let users sign up, log in, and log out, limiting access to password-protected resources using Node.js and Express
- Created a registration form, a login form with Pug and a document schema with keys and additional properties to control the type of data stored in MongoDB
-	Used Bcrypt to hash passwords to make the system more secure
-	Added sessions and cookies for keeping track of user information and stored session data in MongoDB to provide a scalable solution for a production server

How to use:
Download the repo. open the terminal, change directory to the repo. type mongod in the terminal
open another shell, run npm install and then run npm start or nodemon(if you want to change and debug)
open the browser, typle localhost:8000
