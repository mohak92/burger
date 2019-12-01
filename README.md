# Burger

### Overview

A burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). FollowS the MVC design pattern; useD Node and MySQL to query and route data in the app, and Handlebars to generate HTML.

### Project Description

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

* The app will store every burger in a database, whether devoured or not.

### Launch Application
Check out [this deployed version of the site](https://www.google.com/)

#### Directory structure

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
 ### Instructions for local setup
  1. Git clone or download the source code.
  2. Run schema.sql to crete database and tables and run seed.sql to insert seed data by using MySQL Shell or any SQL GUI 
  3. Intall dependencies using the node package manager.
  ```bash
  npm install 
  ``` 
  4. Run the application.
  ```bash
  node server.js
  ``` 
  5. Launch the app by entering http://localhost:8080 in your browser.

### Author
Mohak Tamhane
