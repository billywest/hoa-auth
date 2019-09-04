# hoa-auth

# Initial setup

Initialized our backend using npm and installed necessary packages
Set up a MongoDB database
Set up a server with Node.js and Express
Created a database schema to define a User for registration and login purposes
Set up three API routes, register, login, and currentuser using passport + jsonwebtokens for authentication and validator for input validation
Tested our API routes using Postman

# Setup Frontend and Redux

Set up our frontend using create-react-app
Created static components for our Navbar, Landing, Login and Register pages
Setup Redux for global state management

# Linking Redux with React Components

Link Redux to our components
Display errors from our backend in our React forms
Create protected routes (pages only certain users can access based on their authentication)
Keep a user logged when they refresh or leave the page (in other words, until they either logout or the jwt expires)
