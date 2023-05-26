<h1 align="center">Web Developer Roadmap 2023</h1>

![web roadmap](https://github.com/canopas/web-developer-roadmap/blob/master/images/title_image.png)

Web Developer Roadmap 2023 is a learning path to understand web development, including frontend, backend and cloud(AWS).

## How to Learn Web development?

A web development can be divided into four different parts,

1. Database
2. Backend
3. Frontend
4. Cloud(server)

## Guidelines
- Before starting any practical it's important to conduct research and learn the necessary concepts.

- As you progress through the practical exercises, make sure to apply the new knowledge you've gained in subsequent exercises. Try to allocate no more than 5 days to each practical.

- To keep track of your progress and share your work with your team lead, create a repository on GitLab where you can upload your completed exercises for review.

- To stay organized and track your progress, create tickets on ClickUp for each practical exercise. Each ticket should include a detailed description of the exercise, as well as an estimate of story points.

- As you work on each practical exercise, move the corresponding ticket from the "To-Do" queue to the "Done" queue to keep track of your progress. This will help you stay focused and motivated as you work through the roadmap.

- Follow the `best practices` and `coding standards` of perticuler languages for implementation.

# Useful references

These references provides basic knowledge, that is necessary before diving into web development and serve as starting points for beginners. If you have prior knowledge and experience in web development, you can skip this section. 

- [Command line interface - CLI](https://ubuntu.com/tutorials/command-line-for-beginners#4-creating-folders-and-files)
- [Version control system - VCS](https://about.gitlab.com/topics/version-control/) and [Git](https://about.gitlab.com/topics/version-control/what-is-git-version-control/)
- [Backend vs Frontend](https://www.geeksforgeeks.org/frontend-vs-backend/)
- [Document object model - DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [REST APIs](https://blog.postman.com/rest-api-examples/)
- [JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [Coding standards](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)
- [Docker](https://www.ibm.com/topics/docker)
- [Cloud](https://www.cloudflare.com/en-gb/learning/cloud/what-is-the-cloud/) and [AWS](https://www.guru99.com/what-is-aws.html)

# Table of contents

1. [Basic commands and Version Control](https://github.com/canopas/web-developer-roadmap#1-basic-commands-and-version-control)
2. [HTML/CSS](https://github.com/canopas/web-developer-roadmap#2-htmlcss)
3. [Database](https://github.com/canopas/web-developer-roadmap#3-database)
4. [PHP](https://github.com/canopas/web-developer-roadmap#4-php)
5. [Javascript](https://github.com/canopas/web-developer-roadmap#5-javascript)
6. [Typescript](https://github.com/canopas/web-developer-roadmap#6-typescript)
7. [NodeJS](https://github.com/canopas/web-developer-roadmap#7-nodejs)
8. [VueJS](https://github.com/canopas/web-developer-roadmap#8-vuejs)
9. [Golang](https://github.com/canopas/web-developer-roadmap#9-golang)
10. [ReactJS](https://github.com/canopas/web-developer-roadmap#10-reactjs)
11. [Docker](https://github.com/canopas/web-developer-roadmap#11-docker)

# 1. Basic commands and Version Control

## Practical 1.1

Perform following commands on terminal and write down for review

- Basic commands
  - List all files with details in directory
  - Give only read permission to any file
  - Give all read and write permissions to any file
  - Get IP address of own pc
  - Observe disk space usage
  - View previously executed commands history
  - Linux command to install/uninstall PHP
  - Linux command to start/stop mysql service
  - Write and save any file from terminal

- Version Control
  - Check git status of repository
  - Commit new/updated files into a git repository
  - Push in a git repository
  - Pull new changes from repository
  - Checkout new branch
  - Merge branch into another
  - See commit history
  - Rebase and Squash
  - Write a command to clone [this](https://github.com/canopas/web-developer-roadmap) repo

# 2. HTML/CSS

## Practical 2.1

- Static UI 
  
  - Create HTML project and design static UI given in [reference](https://github.com/canopas/web-developer-roadmap/blob/master/images/static-new.png).
  - Use modern CSS properties like flex or grid to create UI.

## Practical 2.2

- Responsive UI 
  
  - Create HTML project and design [this](https://www.w3schools.com/w3css/tryw3css_templates_food_blog.htm) UI.
  - UI should be responsive for mobile and desktop devices.
  - Use modern CSS properties like flex or grid to create UI.

## Practical 2.3

- Tailwind css
  
  - Configure tailwindcss in project.
  - Create [given](https://github.com/canopas/web-developer-roadmap/blob/master/images/swiper.webm) responsive UI using swiper and tailwindcss.
  - UI should be responsive till 4k devices.

## Practical 2.4

- Animations

  - CSS Hover Effects: 
    - Implement creative hover effects on given elements. 
      - **Button:** Change background and text color on hover
      - **Link:** Add underline floating from left to right on hover
      - **Image:** Rotate left image on hover
    - Utilize CSS transitions, transforms, or animations to add interactive and visually appealing effects when the user hovers over the elements.

  - CSS Text Effects: 
    - Implement various text effects using CSS animations or transitions. 
    - Examples include text color changes, text rotations, text scaling, or text fading. 
    - Play around with different timing functions and animation properties to create visually appealing text effects.
    
  - Loading Spinner: 
    - Create spinner given in the [link](https://github.com/canopas/web-developer-roadmap/blob/master/images/spinner.webm) 
    - Use keyframe animations or CSS transforms to create a effect. 
    - Customize the spinner's appearance and experiment with different animation properties to achieve the desired effect.
  
  - Bounce up and down the circle on clicking on the button
    - Utilize CSS transitions, transforms, or animations to add interactive and visually appealing effects when the user hovers over the elements.
    - Customize the circle's appearance and experiment with different animation properties to achieve the desired effect.

#  3. Database

## Practical 3.1

- Perform following queries in **MySQL**

  - Create a table named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Create table `student_attendances` with fields id, student_id, created_at, presence/absence fields and insert data into it
  - Create a table named `teachers` with fields id, first_name, last_name, subject, interests etc... and insert data into it
  - Create table `teachers_attendances` with fields id, teacher_id, created_at, presence/absence fields and insert data into it
  - Find student's presence/absence on a particular day
  - Find total absence/presence of every student
  - Find absent students with a percentage lower than 70.
  - Find a student who has higest presence
  - Get all student's and teacher's first_name, last_name, full_name, interest, standard, subject and total absence.

## Practical 3.2

- Perform following queries in **MongoDB** (Can use [MongoDBPlayground](https://mongoplayground.net/) to peform queries)
  
  - Create a collection named `students` with fields id, first_name, last_name, standard, percentage, interest, etc... and insert data into it
  - Create table `student_attendances` with fields id, student_id, created_at, presence/absence fields and insert data into it
  - Find students with a percentage lower than 70 and interest in sport.
  - Find total attadence of students who has not interest in sport but interest in reading.
  - Count the total students with a percentage above 80

# 4. PHP

## Practical 4.1

- Simple calulator
  - Create a calculator that can perform basic arithmatic operations like addition, subtraction, multiplication, and division
  - Add two input fields which allow only numeric values
    - Show error if value is not numeric
  - Add buttons for arithmatic operations like addition, subtraction, multiplication, and division
  - Add submit button and print the result in label

## Practical 4.2
- Blog application
    - It should have two roles
      1. Admin
      2. User
    - Implement Register and login/logout functionality for admin
    - Create add/edit/delete posts for admin. It should not be accessible by users.
      - post fields - title, description, created_at, author, category, image
    - Allow admin to disable/enable users to see posts.
    - User can only view the post in descending order.

# 5. JavaScript

## Practical 5.1
- Random Quote Generator
  - Display random technical quotes each time when the user refreshes the page or clicks a button. 
  - Store an array of quotes and use JavaScript to randomly select and display one of them.

## Practical 5.2
- Interactive Form Validation
  - Create a form containing fields like name, email, phone, and password with placeholder.
  - Implement form validation using JavaScript. 
  - Validate input fields for required values, email formats, password strength, and other criteria. - Display error messages for invalid inputs in red color.
  - If all validations will be pass, submit form using AJAX to previously created registartion code in PHP and show popup with success message.

# 6. TypeScript

## Practical 6.1
- BMI Calculator
  - Build a BMI (Body Mass Index) calculator that takes a person's weight and height as input and calculates their BMI. 
  - Add appropriate validations for input fields.
  - Use TypeScript to define the data types for the inputs and outputs and provide a meaningful interpretation of the result.

## Practical 6.2
- File Uploader
  - Implement a file uploader that allows users to upload files to a server. 
  - Allow only `pdf` and `doc` files.
  - Max filesize should be `10kb`.
  - Display progress indicators during the upload process.
  - Show `File uploaded successfully` message after upload

# 7. NodeJS

## Practical 7.1

- Real-time Chat Application
  
  -  Build a real-time chat application using Node.js, Javascript, and a library like Socket.IO. 
  -  Allow users to join chat rooms, send messages, and receive messages in real-time.

## Practical 7.2

- Ecommerce App authorization and admin apis
  
  - Review [Ecommerce App](https://github.com/canopas/web-developer-roadmap/blob/master/ecommerce_web_app_backend.md) requirements.
    - Use expressJs, typescript and sequlize with postgreSQL
    - Create following REST APIs
      - Admin SignUp/SignIn
      - User SignUp/SignIn -- Send mail to the users after signUP from API only
      - Admin APIs -- Only authenticated admins can access these apis
        - Create/Update/Delete categories
        - Create/Update/Delete sub categories
        - Create/Update/Delete products

## Practical 7.3 

- Ecommerce App user apis (continue Practical 8.2)
  
  - Create following User REST APIs -- Only authenticated users can access these apis
    - FindAll/FindOne categories, sub categories, products
    - Get products of given category/subcategory
    - Search product from given string with name, price
    - Favourite/Unfavorite products
    - Send feedback mail to the admin.
  
# 8. VueJS

## Practical 8.1

- Ecommerce Admin panel
   - Review [Ecommerce App](https://github.com/canopas/web-developer-roadmap/blob/master/ecommerce_web_app_backend.md) requirements.
   - Understand lifecycle of vueJS
   - Use tailwind and vite
   - Can use readymade templates
   - Use [nodeJS]() APIs to handle the data
   - Use vuex or pinia store to manage data
   - Create registration/Login forms with all validations
   - Admin should able to create, update, delete and view categories, subcategories and product
   - Admin should able to see all users
   - Implement logout functionality

## Practical 8.2
- Ecommerce website
  - Create website where user can see list of products
  - User should be able to filter products by categories and subcategories
  - Create registration/Login forms with all validations
  - LoggedIn users can fav/unfav products. 
  - Implement logout functionality

# 9. Golang

## Practical 9.1 

- Music APP authorization and admin apis
  
  - Review [Music APP](https://github.com/canopas/web-developer-roadmap/blob/master/music_app_new.md) requirements 
  - Use JWT for authentication
  - Use concepts of golang like go modules, generics, concurrency etc...
  - Create following REST APIs
    - Admin Register/Login
    - User Register/Login
    - Admin APIs -- Only authenticated admins can access these apis
      - Create/Read/Update/Delete artist
      - Create/Read/Update/Delete album
      - Create/Read/Update/Delete track
      - Create/Read/Update/Delete playlist
      - Add/Remove tracks to/from album
      - Add/Remove tracks to/from playlist
      - Get all users

## Practical 9.2 

- Music APP user apis (continue Practical 9.1)

  - Create following User REST APIs -- Only authenticated users can access these apis
    - Fetch all albums
    - Fetch all tracks
    - Fetch all tracks by album Id
    - Fetch all playlists
    - Get playlist and its tracks by playlist id
    - Favourite/unfavourite tracks
    - Retrieve favourite/unfavourite tracks of own

## Practical 9.3

- Unit tests and Documentation (continue Practical 9.1)
  
  - Write test for all errors and response
  - Write unit test for following APIs from [Music APP](https://github.com/canopas/web-developer-roadmap/blob/master/music_app_new.md) 
    - Create playlist
    - Delete track
    - Get playlist and its tracks by playlist id
    - Favourite/unfavourite tracks
  - Write API documentation for the given APIs.
    - Should contain following fields
      - Method
      - Endpoint
      - Path params/Query params
      - Description
      - Header
      - Request
      - Response

# 10. ReactJS

## Practical 10.1
- Music App Admin panel
   - Review [Music APP](https://github.com/canopas/web-developer-roadmap/blob/master/music_app_new.md) requirements 
   - Use tailwind, vite and typescript
   - Can use readymade templates
   - Use [Golang]() APIs to handle the data
   - Create a admin panel which will cover all the admin APIs.

## Practical 10.2
-  Website
   - Create webapp which will cover all User APIs.
   - Can refer [spotify](https://open.spotify.com/) UI.
   - Use tailwind, vite and typescript
   - Allow users to favourite/unfavourite tracks if they have loggedIn otherwise redirect to login page on click on fav/unfav

# 11. Docker

## Practical 11.1

Perform following commands

- Pull latest mysql and nginx image
- List the docker images
- List the docker volumes
- Run nginx container on 8000 port
- Run mysql container on 3307 port with volume
- List the current running containers
- List the file with its details inside the nginx container
- Stop nginx container
- Remove nginx container and image
- Show logs of docker container
- Show latest 100 logs of docker container
