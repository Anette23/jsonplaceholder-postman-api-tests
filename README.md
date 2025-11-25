# Postman JSONPlaceholder API

This repository contains a Postman collection for testing CRUD operations (Create, Read, Update, Delete) on the JSONPlaceholder fake API. 
It demonstrates basic API testing, including positive and negative scenarios.

## Collection Contents

- **GET /posts** – Retrieve all posts  
- **GET /posts/:id** – Retrieve a specific post  
- **POST /posts** – Simulate creating a new post  
- **GET /posts** – Retrieve all posts again to check the new post 
- **PUT /posts/:id** – Update an existing post  
- **DELETE /posts/:id** – Delete a post  
- **GET /posts/9999** – Negative test: request non-existent post  

## Important Notes

- JSONPlaceholder is a fake API, so **POST, PUT, and DELETE requests do not actually modify the data**.  
- Status codes (**201, 200, 404**) and responses are returned for testing purposes.  
- This collection is intended for **practicing API testing** with Postman.  

## How to Use

1. Import the JSON collection file into Postman.  
2. Run the requests to test CRUD operations.  
3. Observe responses and status codes.  

