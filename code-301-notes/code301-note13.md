
# Read 13: More CRUD

# CRUD Basics

#### 1. Which HTTP method would you use to update a record through an API?

PUT and PATCH.

#### 2. Which REST methods require an ID parameter?

GET, POST and PUT. POST method typically does not require an ID parameter in the URL since the server generates the resource identifier (ID) upon creation.
In some cases, APIs might have endpoints where an ID is included for creating a resource with a specific ID if supported by the server.

# Building a CRUD API

#### 1. What’s the relationship between REST and CRUD?

REST (Representational State Transfer) is an architectural style for creating web services that are scalable, flexible and easy to maintain. CRUD (Create, Read, Update, Delete) represents the basic operations that can be performed on resources in a system. HTTP methods are used to perform CRUD operations. 

#### 2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

Creating a RESTful API involves designing, implementing and exposing endpoints that adhere to REST principles.

- Define requirements and design endpoints.
- Choose a technology stack.
- Implement the endpoints based on the designed API structure.
- Set up a database or data storage mechanism to persist the data associated with your API.
- Test your API endpoints thoroughly to ensure they behave as expected, and handle errors. 

# Things I want to know more about