# EasyShop

Welcome to EasyShop! We are an online e-commerce shop that sells household essentials and much more. The homepage is a simple, yet clean, user experience that features an ample amount of products, a login option, cart viewing option, and item filtering function.

## Summary
This project is intended to be a full-stack shopping application with an emphasis in the backend. In this project, we were presented with this operational application that was in it's beta phase and my duty is to take what we had and fix any errors, bugs, and functions. In order to do so, we use Postman to test API endpoints for validation, MySQL for it's database, and Java (IntelliJ) as it's foundation.


> Phase 1:

In this phase, our emphasis was to focus on the CategoriesController it's respective DAO. In these two respectively, I added its missing methods, functions and annotations which include creating, updating and deleting, along with CRUD operation which lets the user to freely browse items in the front end.

> Phase 2:

Phase 2 focused more on the ProductsController. Here, there was issues in regards to the search and filter functionalities. Here, I updated the ProductsController to call correct methods and CRUD operations for the products.

> Phase 3:

This part was intended for us to create the shopping cart. This gives them the ability to add items to their cart for future purchases, and can only be accessed by logged in users. Just like other phases, I added CRUD operation to allow items to be properly grouped, added, updated, and saved.

> Phase 4:

This is mainly focused on User Profiles. Here, I added functionality for users to be able to log into their accounts or create a new one. Here, we create a controller that works cohesively with it's respective DAO to recall certain actions (register/login).

> Phase 5:

In the last phase, the main goal is to allow the user to check out. Here, the shopping cart should be emptied and placed into an Order. To do this, I created an OrdersController, OrderDAO and it's "MySql-" counterpart. 
