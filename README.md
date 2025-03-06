# FastAPI
4 APIs mainly list, info, add, update for Product API /product/list – List all products with pagination of 10 records per page API /product/{pid}/info – View information about the requested product ID API /product/add – Adds new product to database API /product/{pid}/update – Updates existing product with product ID to database
Clone the Repository
Create a Virtual Environment
Install Dependencies
Set Up MySQL Database
Apply Migrations
Run the FastAPI Server
    POST   /products/      Create a new product
    GET    /products/      Get all products
    GET    /products/{id}  Get a single product by ID
    PUT    /products/{id}  Update a product by ID

FastAPI automatically generates interactive API docs:
Swagger UI: http://127.0.0.1:8000/docs
