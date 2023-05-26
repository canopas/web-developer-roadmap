<h1 align="center">Web Developer Roadmap 2022</h1>

![web roadmap](https://github.com/canopas/web-developer-roadmap/blob/master/images/title_image.png)

Web Developer Roadmap 2022 is a learning path to understand web development, including frontend, backend and cloud(AWS).

## How to Learn Web development?

A web development can be divided into four different parts,

1. Database
2. Backend
3. Frontend
4. Cloud(server)

This roadmap consists of widely used technologies/frameworks for frontend and backend.
It also includes overview about cloud(AWS) and some information about server.

# Table of contents

- [Sprint 1 - Basic linux commands, Version control, Web technologies and coding conventions](https://github.com/canopas/web-developer-roadmap#sprint-1---version-control-basic-web-technologies-and-coding-conventions)
- [Sprint 2 - Docker, Databases and PHP](https://github.com/canopas/web-developer-roadmap#sprint-2---docker-databases-and-php)
- [Sprint 3 - Golang](https://github.com/canopas/web-developer-roadmap#sprint-3---golang)
- [Sprint 4 - Node.js](https://github.com/canopas/web-developer-roadmap#sprint-4---nodejs)
- [Sprint 5 - Vue.js](https://github.com/canopas/web-developer-roadmap#sprint-5---vuejs)
- [Sprint 6 - Useful concepts](https://github.com/canopas/web-developer-roadmap#sprint-6---useful-concepts)

## Sprint 1 - Basic linux commands, Version control, Web technologies and coding conventions

### Practical 1.1 - Basic commands and Version control

- Write a commands for following operations in terminal
  - List all files with details in directory
  - Give only read permission to any file
  - Give all read and write permissions to any file
  - Get IP address of own pc
  - Observe disk space usage
  - View previously executed commands history
  - Linux command to install/uninstall PHP
  - Linux command to start/stop mysql service
  - Write and save any file from terminal

#### References

- [Basic linux commands](https://www.digitalocean.com/community/tutorials/linux-commands)

- [What Is Version Control?](https://about.gitlab.com/topics/version-control/)
- How to use git
  - [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
  - [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.freecodecamp.org/news/git-the-laymans-guide-to-understanding-the-core-concepts/)
  - [Git commands](https://dzone.com/articles/top-20-git-commands-with-examples)

### Practical 1.2 - Basic web technologies with coding conventions

- UI design with coding standards
  - Design static UI given in the [link](https://github.com/canopas/web-developer-roadmap/blob/master/images/static.png) 
  - Design responsive UI given in the [link](https://www.w3schools.com/w3css/tryw3css_templates_food_blog.htm) 

#### References

- HTML5

  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 2 and 3
  - [Basic HTML and HTML5 from Free Code Camp](https://www.freecodecamp.org/)

- CSS3
  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 4 and 5
  - [Bootstrap from Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 6 and 8
  - [What is Flexbox?](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Bootstrap from Frontend libraries in Free Code Camp](https://www.freecodecamp.org/)
  - [Finish Responsive web design certification course from Free Code Camp](https://www.freecodecamp.org/)

- Code formatting and best practices
  - [25 Most Used VS Code Shortcuts](https://www.crio.do/blog/vs-code-shortcuts/)
  - [Code formatting in VS Code](https://mkyong.com/vscode/how-to-format-source-code-in-visual-studio-code-vscode/)
  - [Web development best practices](https://code.tutsplus.com/tutorials/30-css-best-practices-for-beginners--net-6741)


### Practical 1.3

- Unit converter
  - Create a unit converter that should take input from users and output the value in the asked unit (conversion units can be centimeters, meters, and kilometers)

#### References

- Javascript & jQuery

  - [Basic javascript from Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 9 and 10
  - [Basic javascript, ES6, Regular expressions, and Debugging from Free Code Camp](https://www.freecodecamp.org/)
  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 11 and 13
  - [JSON, APIs, and ajax from Free Code Camp](https://www.freecodecamp.org/)
  - [Finish Javascript algorithms and data structures from Free Code Camp](https://www.freecodecamp.org/)
  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 14 to 16
  - [Finish Frontend libraries projects from Free Code Camp](https://www.freecodecamp.org/)
  - Difference between == and ===
  - [Basics of jQuery](https://learn.jquery.com/using-jquery-core/)

- Coding conventions
  - [Coding standards-1](https://medium.com/@luqman.qureshi/think-twice-code-once-c49faa8cd18)
  - [Coding standards-2](https://google.github.io/styleguide/htmlcssguide.html#:~:text=Use%20only%20lowercase.,with%20the%20exception%20of%20strings)

## Sprint 2 - Docker, Databases and PHP

### Practical 2.1

- Install MySQL using Docker
- Install MongoDB using Docker

#### References

- [What is docker](https://opensource.com/resources/what-docker)
- [Getting started with docker](https://docs.docker.com/get-started/overview/)
- [Install MySQL using Docker](https://hub.docker.com/_/mysql)
- [Install MongoDB using Docker](https://hub.docker.com/_/mongo/)

### Practical 2.2

- Perform following queries in MySQL

  - Create a table named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Create table `student_attendances` with fields id, created_at, presence/absence fields and insert data into it
  - Create a table named `teachers` with fields id, first_name, last_name, subject, interests etc... and insert data into it
  - Create table `teachers_attendances` with fields id, created_at, presence/absence fields and insert data into it
  - Prepare queries to find student's presence/absence on a particular day
  - Find total absence/presence of every student
  - Find absent students with a percentage lower than 70.
  - Find a student who has higest presence
  - Get all student's and teacher's first_name, last_name, full_name, interest, standard, subject and total absence.

- Perform following queries in MongoDB (Can use [MongoDBPlayground](https://mongoplayground.net/) to peform queries)
  - Create a collection named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Form a query to find students with a percentage lower than 70 and interest in sport.
  - Count the total students with a percentage above 70

#### References

- [Web Development Bootcamp course udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 24 and 25
- [Mysql Subquery](https://www.mysqltutorial.org/mysql-subquery/) and [Union query](https://www.mysqltutorial.org/sql-union-mysql.aspx)

### Practical 2.3

- Create a Blog application with following requirements using PHP
  - It should have two sides
    - 1. Admin
    - 2. User
  - Implement Register and login functionality for both user and admin
  - Admin can add posts ( post fields - title, description, created_date, author, category, image )
  - Admin can decide which user can see the post
  - Added Posts will be visible on user side (latest first)

#### References

- [PHP: Language Reference](https://www.php.net/manual/en/langref.php)
- [PHP: Introduction](https://www.w3schools.com/php/)
- [Coding standard](https://flowframework.readthedocs.io/en/stable/TheDefinitiveGuide/PartV/CodingGuideLines/PHP.html)

#### Basic Concepts

- Installation WAMP/MAMP/XAMPP
- How it exactly works ?
- Basic Syntax
- Variables, Constants, Operators & Control Structures
- Conditions, Loops, Switch cases
- Arrays, String and various string functions
- Functions
- Includes & Required
- Classes & Objects & Constructors
- Namespaces
- Extensions
- Exceptions
- JSON Encode & Decode
- Sessions
- Cookies
- File Manipulation
- Indexed Array vs Associative Array
- Object vs stdObject
- Timeout of PHP script

#### Predefined variables

- http://php.net/manual/en/reserved.variables.php
- $GLOBAL
- $\_SERVER
- $\_GET
- $\_POST
- $\_FILES
- $\_REQUEST
- $\_SESSION
- $\_COOKIE

#### Advanced options

- Interfaces
- Traits
- Crons
- Composer
- php.ini tweaks

#### Keywords

- Private
- Public
- Static

## Sprint 3 - Golang

### Practical 3.1

- Implement [Music App](https://github.com/canopas/web-developer-roadmap/blob/master/music_app.md) with given requirements

#### Basic concepts

- [Why Go?](https://yourbasic.org/golang/advantages-over-java-python/)
- [Run the hello world program in Go](https://golang.org/doc/tutorial/getting-started)
- [Go modules](https://golang.org/doc/tutorial/create-module)
- [Gin framework](https://www.educative.io/edpresso/what-is-gin-in-golang)
- Constants, variable types
- Functions, multi return functions, init()
- Packages and import
- Conditional Statements and Loops
- Arrays and slices
- Pointers, structs, and methods
- Error handling
- [gofmt](https://go.dev/blog/gofmt)
- [Best practicies](https://go.dev/talks/2013/bestpractices.slide#20)

- Others
  - [JWT](https://jwt.io/introduction)
  - [JSON](https://www.w3schools.com/whatis/whatis_json.asp)
  - [REST API](https://www.edureka.co/blog/what-is-rest-api/)

#### Advance concepts

- Maps in Go
- Concurrency and Goroutine
- defer
- Error handling
- Panic and recover
- Reflection
- Type conversion
- File manipulations
- Logging
- Authentication with JWT (JSON Web Token)

#### Packages

- [Gin](https://github.com/gin-gonic/gin)
- [Mysql package](https://github.com/jmoiron/sqlx)
- [net/http](https://golang.org/pkg/net/http/)
- [File compressor](https://github.com/gin-contrib/gzip)
- [Logging](https://github.com/sirupsen/logrus)
- [Mongodb](https://godoc.org/go.mongodb.org/mongo-driver/mongo)
- [ioutil](https://golang.org/pkg/io/ioutil/)
- [os](https://golang.org/pkg/os/)
- [strings](https://golang.org/pkg/strings/?m=all)
- [parse static file to binary](https://github.com/markbates/pkger)
- [null value handler](https://github.com/guregu/null/tree/v3.5.0)
- [JWT](https://github.com/dgrijalva/jwt-go)
- [socket.io](https://github.com/googollee/go-socket.io)
- [sentry](https://github.com/evalphobia/logrus_sentry)

## Sprint 4 - Node.js

### Practical 4.1

- Implement one-one real time chat application

### Practical 4.2

- Implement an [Ecommerce App](https://github.com/canopas/web-developer-roadmap/blob/master/ecommerce_web_app_backend.md) with given requirements

#### References

- [yarn](https://classic.yarnpkg.com/en/docs/getting-started)
- [npm](https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/)
- [yarn vs npm](https://www.knowledgehut.com/blog/web-development/yarn-vs-npm)
- [node](https://nodejs.org/en/about/)
- [Why node.js?](https://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js)
- Basic concepts:
  - [CommonJS and ESModule](https://www.freecodecamp.org/news/modules-in-javascript/)
  - [Console](https://nodejs.org/api/console.html)
  - [Scope](https://scotch.io/tutorials/understanding-scope-in-javascript)
  - ['this' keyword part 1](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20%26%20object%20prototypes/ch1.md)
  - ['this' keyword part 2](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20%26%20object%20prototypes/ch2.md)
  - Understanding package.json
  - Import/export require
  - Callbacks
  - async-await
  - async.waterfall()
  - [Ref](https://webapplog.com/node-js-fundamentals-a-concise-overview-of-the-main-concepts/)
  - [Event loop](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)
  - Node mailer to send emails
  - [Best practices](https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399)

- Express.js
  - [Installation](https://expressjs.com/en/starter/installing.html)
  - [Express Generator](https://expressjs.com/en/starter/generator.html)
  - [Routing](https://expressjs.com/en/starter/basic-routing.html)
  - [Host static files](https://expressjs.com/en/starter/static-files.html)
  - [Template engine(ejs)](https://expressjs.com/en/guide/using-template-engines.html)
  - Body parser

## Sprint 5 - Vue.js

### Practical 5.1

- Implement frontend of [Ecommerce App using Vue.js](https://github.com/canopas/web-developer-roadmap/blob/master/ecommerce_web_app_frontend.md) with given requirements

#### References

- [Get started with Vue.js](https://v3.vuejs.org/)
- [Tailwind css for beginners](https://www.youtube.com/watch?v=bxmDnn7lrnk&list=PL4cUxeGkcC9gpXORlEHjc5bgnIi5HEGhw)
- [Tailwind css tutorial](https://tsh.io/blog/tailwind-css-tutorial/)
- [Pinia](https://pinia.vuejs.org/introduction.html)

- Concepts
  - What is vue.js ?
  - Getting started
  - Installation
  - Application and component instances
  - Template syntax
  - Data properties and Methods
  - Computed Properties and Watchers
  - Class and Style Bindings
  - Conditional rendering, conditional style binding
  - List rendering
  - Event Handling
  - Form input bindings
  - Component Basics
  - Props
  - Component registration
  - Slots
  - Template refs
  - State management

## Sprint 6 - Useful concepts

#### Concepts

- [Http Protocols](https://www.tutorialspoint.com/http/)
- [Asynchronous vs synchronous behaviour](https://www.geekinsta.com/difference-between-synchronous-and-asynchronous-programming/)
- Caching(Understanding of Redis)
- Testing : unit and feature testing overview
- [Docker in detail](https://docker-curriculum.com/)
- Nginx vs Apache server
- Server Login with Password/SSH Keys
- IP tables
- Php-fpm and httpd
- SSH, SSL, certificates and keys

#### Cloud

- [What is AWS?](https://searchaws.techtarget.com/definition/Amazon-Web-Services)
- S3
- EC2
- RDS
- Elasticache
- Route 53
- SES
- Cloudwatch
- VPC
- [AWS Lamda](https://www.guru99.com/aws-lambda-function.html)
- [AWS API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [Microservices](https://www.educative.io/blog/microservices-architecture-tutorial-all-you-need-to-get-started?affiliate_id=5082902844932096&utm_source=google&utm_medium=cpc&utm_campaign=platform2&utm_content=ad-1-dynamic&gclid=Cj0KCQjwk8b7BRCaARIsAARRTL6juttpPjrgo_hRVSuYm_PvM-KenAvrRRsxNxt1zyfp8R2mQn5_zHwaAtaiEALw_wcB)
- [What are microservices? How AWS implement it?](https://relevant.software/blog/microservices-on-aws/)
- [Microservices implementation using Go](https://blog.canopas.com/golang-serverless-microservices-with-gin-f3c2a4943a6d)

#### Additional

- [Golang roadmap](https://github.com/Alikhll/golang-developer-roadmap)
- [NodeJS roadmap](https://github.com/aliyr/Nodejs-Developer-Roadmap)
