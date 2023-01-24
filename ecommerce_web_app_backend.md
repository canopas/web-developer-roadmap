# E-commerce App backend using NodeJS

You need to build Backend of given APP using raw queries and [sequelize](https://sequelize.org/docs/v6/getting-started/).
  
## Requirements

Create 2 projects, 
- using Raw queries 
- using Sequelize

### Technologies

- Decide database structure(tables, relations and models)
- Can use [typeScript/javaScript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html)
- Use [express.js](https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm) and [ejs](https://www.digitalocean.com/community/tutorials/how-to-use-ejs-to-template-your-node-application) template engine

### Application will have two type of users :

- Admin - Should have Read/Write access
- User - Should have Read access only, except Favourite/Unfavourite functionality

**Note:** Admin is also a user. Admin should have all access same as user. Additionally they can modify the content(categories, sub categories, products).


## Admin APIs

- SignUp
- SignIn
- Create/Update/Delete categories
- Create/Update/Delete sub categories
- Create/Update/Delete products

## User APIs

- SignUp - Send mail to the users after signUP from API only
- SignIn
- FindAll and FindOne categories
- FindAll and FindOne sub categories
- FindAll and FindOne products
- Get products of given category/subcategory
- Search product from given string with name, price
- Favourite/Unfavourite products
- Get own favourited products
- Create API to send mail to the admin  regarding to issues.


