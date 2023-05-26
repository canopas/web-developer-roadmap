# E-commerce App backend using NodeJS

### Application will have two type of users :

- Admin - Should have Read/Write access.
- User - Should have Read access only.

**Note:** Admin is also a user. Admin should have all access same as user. Additionally they can modify the content(categories, sub categories, products).

## Description

- This E-commerce app contains products with categories and subcategories.
  - Example: 
      - category: food
      - subcategory: chinese, italian, maxican
      - product: manchurian, pasta, pizza
- Admin panel, 
  - It is used to add and manage data by admins
  - admins can perform CRUD operations of products, categories and subcategories
  - Admin should requires to SignUp/SignIn to access admin panel
- In Website,
  - It should be accessible by all users and provide a interactive UI for user to use our ecommerce app.
  - Users can see all products and filter them by categories and subcategories
  - Allow users to favourite/unfavourite products if they have loggedIn otherwise redirect to login page on click on fav/unfav

