# Angular Todo App

## Overview

### What is this app for?

This is a Todo app. It helps users to keep track of any things that they have todo.

### What does it do?

This app will allow users to register and login. Once the users have done that, they'll be able to create items to add to thier todo list. Once they've created their todo list, theu'll be able to update the status of each item and even delete items!

### How does it work?

This app uses JSON Web tokens to authenticate users and keep them logged in. All the datais consume from an API hosted on Heroku using AngularJS. The site is styled with Bootstrap.

## Features

### Existing Features
- None yet!

### Features Left to Implement
- User Based Features
    - Registration
    - Login
    - Logout
- Todo Based Features
    - Creating Todo Items
    - Retrieving Todo Items
    - Updating Todo Items
    - Deleting Todo Items

## Tech Used

### Some the tech used includes:
- [AngularJS](https://angularjs.org/)
  - We use **AngularJS** to handle page routing, we also use it to make calls tothe REST API and bulid custom directives
- [Bootstrap](http://getbootstrap.com/)
  - We use **Bootstrap** to give our project a simple, responsive layout
- [npm](http://www.npmjs.com/)
  - We use **npm** to help manage some of the dependencies in our application#
- [bower](https://bower.io/)
  - **Bower** is used to manage the installation of our libraries and frameworks

## Contributing

## Getting the code up and running
1. Firstly you will need to clone this repository by runningthe ```git clone<https://github.com/Jpsteward/angular-todo/tree/master>``` command
2.After you've done that you'll need to make sure you have **npm** and **bower** installed
  1. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
  2. Once you've done this you'll need to run the following command:
    `npm install -g bower # this may require sudo on Mac/Linux `
3. Once **npm** and **bower** are installed, you'll need toinstall all of the dependencies in *package.json* and*bower.json*
   ```
   npm install

   bower install
  ```

4. After those dependencies have been installed you'll need tomake sure you have **http-server** installed. You can install this by running the following: ```npm install-g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server -c-1```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request.


