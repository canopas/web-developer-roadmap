<h1 align="center">Web Developer Roadmap 2022</h1>

![alt text](https://github.com/canopas/web-developer-roadmap/blob/master/images/title_image.jpeg)

Web Developer Roadmap 2022 is a learning path to understand web development, including frontend, backend and cloud(AWS).

## How to Learn Web development?

In web development, there are mainly four ends mainly.

1. Backend
2. Frontend
3. Database
4. Cloud(server)

This roadmap consists of widely used technologies/frameworks for frontend and backend.
It also includes overview about cloud(AWS) and some information about server.

# Table of contents

- [Sprint 1](https://github.com/canopas/web-developer-roadmap#sprint-1)
- [Sprint 2](https://github.com/canopas/web-developer-roadmap#sprint-2)
- [Sprint 3](https://github.com/canopas/web-developer-roadmap#sprint-3)
- [Sprint 4](https://github.com/canopas/web-developer-roadmap#sprint-4)
- [Sprint 5](https://github.com/canopas/web-developer-roadmap#sprint-5)
- [Sprint 6](https://github.com/canopas/web-developer-roadmap#sprint-6)

## Sprint 1 - Version control, Basic web technologies and coding conventions

#### Practical 1.1

- Perform following operations in gitlab
  - Create a project, create a repository to GitLab
  - Add new files into a git repository
  - Modify some files and commit them into a git repository
  - Push in a git repository
  - Create Commits, tags, and branches
  - Checkout new branch
  - Merge branch into another
  - Rebase
  - Create merge request

#### References

- [What Is Version Control?](http://guides.beanstalkapp.com/version-control/intro-to-version-control.html)
- How to use git
  - [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
  - [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.freecodecamp.org/news/git-the-laymans-guide-to-understanding-the-core-concepts/)
  - [Git commands](https://dzone.com/articles/top-20-git-commands-with-examples)

#### Practical 1.2

- UI Design
  - Design static UI given in the [link](https://github.com/canopas/web-developer-roadmap/blob/master/images/static.png)
  - Design responsive UI given in the [link](https://www.w3schools.com/w3css/tryw3css_templates_food_blog.htm)

#### References

- HTML5

  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 2 and 3
  - [Basic HTML and HTML5 from Free Code Camp](https://www.freecodecamp.org/)

- CSS3
  - [Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 4 and 5
  - [Bootstrap from Web development bootcamp course on udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 6 and 8
  - [Bootstrap from Frontend libraries in Free Code Camp](https://www.freecodecamp.org/)
  - [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Finish Responsive web design certification course from Free Code Camp](https://www.freecodecamp.org/)

#### Practical 1.3

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

#### Practical 2.1

- Install MySQL using Docker
- Install MongoDB using Docker

#### References

- [What is docker](https://opensource.com/resources/what-docker)
- [Getting started with docker](https://docs.docker.com/get-started/overview/)
- [Install MySQL using Docker](https://www.softwaretestinghelp.com/mysql-docker/)
- [Install MongoDB using Docker](https://www.bmc.com/blogs/mongodb-docker-container/)

#### Practical 2.2

- Perform following queriesin MySQL

  - Create a table named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Create table `student_attendances` with fields id, created_at, P/A fields and insert data into it
  - Prepare queries to find student's presence/absence on a particular day
  - Find total absence/presence of every student
  - Find absent students with a percentage lower than 70.

- Perform following queries in MongoDB
  - Create a collection named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Form a query to find students with a percentage lower than 70 and interest in sport.
  - Count the total students with a percentage above 70

#### References

- [Web Development Bootcamp course udemy](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12299746?start=0#overview) - section 24 and 25

#### Practical 2.3

- Create a Blog application with following requirements
  - It should have two sides
    - 1. Admin
    - 2. User
  - Implement Register and login functionality for both user and admin
  - Admin can add posts ( post fields - title, description, created_date, author, category, image )
  - Admin can decide which user can see the post
  - Added Posts will be visible on user side (latest posts first)

#### References

- [PHP: Language Reference](https://www.php.net/manual/en/langref.php)
- [PHP: Introduction](https://www.w3schools.com/php/)

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

### Advanced options

- Interfaces
- Traits
- Crons
- Composer
- php.ini tweaks

### Keywords

- Private
- Public
- Static

## Sprint 3 - Golang

#### Practical 3.1

- Implement APIs for music application with [given requirements](https://github.com/canopas/web-developer-roadmap/music_app.md)

#### References

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
- [sentry logging](https://github.com/evalphobia/logrus_sentry)

## Sprint 4 - Node.js

#### Practical 4.1

- Implement one-one real time chat application

#### Practical 4.2

- Implement an [Ecommerce Web application](https://github.com/canopas/web-developer-roadmap/ECOMMERCEAPP.md) with given requirements

#### References

- [npm](https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/)
- [node](https://nodejs.org/en/about/)
- [Why node.js?](https://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js)
- Basic concepts:

  - [Console](https://nodejs.org/api/console.html)
  - [Scope](https://scotch.io/tutorials/understanding-scope-in-javascript)
  - ['this' keyword part 1](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20%26%20object%20prototypes/ch1.md)
  - ['this' keyword part 2](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20%26%20object%20prototypes/ch2.md)
  - Understanding package.json
  - Importing exporting require
  - Callbacks
  - async-await
  - async.waterfall()
  - [Ref](https://webapplog.com/node-js-fundamentals-a-concise-overview-of-the-main-concepts/)
  - [Event loop](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)
  - Node mailer to send emails

- Express.js
  - [Installtion](https://expressjs.com/en/starter/installing.html)
  - [Express Generator](https://expressjs.com/en/starter/generator.html)
  - [Routing](https://expressjs.com/en/starter/basic-routing.html)
  - [Host static files](https://expressjs.com/en/starter/static-files.html)
  - [Template engine(ejs)](https://expressjs.com/en/guide/using-template-engines.html)
  - Body parser

## Sprint 5 - Vue.js

#### Practical 5.1

- Implement an [Ecommerce App using Vue.js](https://github.com/canopas/web-developer-roadmap/ECOMMERCEAPP.md) with given requirements

#### References

- [Get started with Vue.js](https://v3.vuejs.org/)

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
- Basic linux commands

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
