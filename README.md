Spring Boot Project with hibernate, h2 and PostgreeSQL

This is a Spring Boot project that implements a set of controllers for the Category, Order, Product and User entities. Each controller provides RESTful endpoints to perform CRUD operations on the respective entities.

Available endpoints:
1. CategoriesController
List All Categories
- Endpoint: GET /categories
- Description: Returns a list of all categories.
Search Category by ID
- Endpoint: GET /categories/{id}
- Parameters Path: {id} - ID of the category to be searched for
- Description: Returns a specific category based on the ID provided.

2. OrderController
List All Orders
- Endpoint: GET /orders
- Description: Returns a list of all orders.
Search Order by ID
- Endpoint: GET /orders/{id}
- Parameters Path: {id} - ID of the order to be searched for
- Description: Returns a specific order based on the ID provided.

3. ProductController
List All Products
- Endpoint: GET /products
- Description: Returns a list of all products.
Search Product by ID
- Endpoint: GET /products/{id}
- Parameters Path: {id} - ID of the product to be searched for
- Description: Returns a specific product based on the ID provided.

4. UserController
List All Users
- Endpoint: GET /users
- Description: Returns a list of all users.
Search User by ID
- Endpoint: GET /users/{id}
- Parameters Path: {id} - ID of the user to be searched for
- Description: Returns a specific user based on the ID provided.
Insert New User
- Endpoint: POST /users
- Request body: JSON representing the details of the new user
- Description: Inserts a new user and returns the details of the user created.
Update Existing User
- Endpoint: PUT /users/{id}
- Parameters Path: {id} - ID of the user to be updated
- Request Body: JSON representing the details of the updated user
- Description: Updates an existing user based on the ID provided.
Delete User by ID
- Endpoint: DELETE /users/{id}
- Parameters Path: {id} - ID of the user to be deleted
- Description: Deletes a specific user based on the ID provided.

Database configurations
The project has settings for different database environments:
- Development Environment (H2): application-dev.properties
- Test Environment (H2): application-test.properties
