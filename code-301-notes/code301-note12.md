# Read 11: CRUD

# Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

100’s: These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

200’s: These are the success codes. They tell the client that its request was accepted. Code 202 is used for asynchronous processing and it means that all validation requirements were met at the time of sending.

300’s: These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.

400’s: These are the client error codes. They are all about invalid requests a client sent to a server, which can be caused by timeouts, wrong URI, missing authentication, etc.

500’s: These are the server error codes, often associated with overwhelmed servers, unreachable servers behind proxies, or client requests that trigger error exceptions on the server. 

#### What is a status code 202?

202 is used for asynchronous processing. It means that the request was accepted and that all validation requirements were met at the time of sending. However, the request may or may not be processed successfully. 

#### What is a status code 308?

 308 means permanent redirect. This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. 

#### What code would you use if an update didn’t return data to a client?

204

#### What code would you use if a resource used to exist but no longer does?

308

#### What is the ‘Forbidden’ status code?

403

# Build A REST API With Node.js, Express & MongoDB

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Keeping sensitive information like database credentials in a .env file adds a layer of security. When code is shared or pushed to version control (like Git), sensitive information won't be exposed. This helps to avoid sharing credentials accidentally or exposing them in public repositories.

#### What is middleware?

Middleware refers to functions or pieces of code that have access to the request and response objects within an HTTP application's request-response cycle. Middleware functions can perform various tasks, modify request or response objects, end the request-response cycle, or call the next middleware function in the stack.

#### What does app.use(express.json()) do?

`app.use(express.json())` is middleware used to parse incoming requests with JSON payloads. It is a built-in middleware provided by the Express framework.

#### What does the /:id mean in a route?

the /:id in a route represents a route parameter. It's a placeholder in the route path that captures whatever value is specified in that segment of the URL.
The :id syntax in the route pattern acts as a placeholder that matches any value within that segment of the URL. 

#### What is the difference between PUT and PATCH?

The PUT method is used to update or replace an entire resource or entity at a specific URL. The PATCH method is used to partially update a resource at a specific URL.

#### How do you make a default value in a schema?

Default values can be defined by using the default property within the field definition.

#### What does a 500 error status code mean?

Internal server error.

#### What is the difference between a status 200 and a status 201?

The status code 200 indicates that the request was successful and the server processed the request without any issues. The status code 201 indicates that the request has been fulfilled, and a new resource has been created as a result of the request. 201 is typically used in response to POST requests where the server successfully creates a new resource based on the information provided in the request.

## Things I want to know more about 