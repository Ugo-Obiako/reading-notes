# Read 08: APIs

# API Design Best Practices

#### 1. What does REST stand for?

REST stands for Representational State Transfer.

#### 2. REST APIs are designed around a ____.

resource

#### 3. What is an identifier of a resource? Give an example.

An identifier of a resource is known as Uniform Resource Identifier (URI) e.g a URL that specifies the location of a web page.

#### 4. What are the most common HTTP verbs?

GET, POST, PUT, PATCH, DELETE

#### 5. What should the URIs be based on?

URIs should uniquely identify a resource. URIs should be consistent, predictable, readable, understandable, maintainable and Scalable.

#### 6. Give an example of a good URI.

https://www.example.com/v1/products/123

#### 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A "chatty" web API refers to an API design where multiple, often small or fine-grained requests are required to perform a single task or retrieve a specific set of data. A chatty API typically necessitates a high number of requests/responses between the client and the server to accomplish a particular operation or retrieve related data. This causes increased network traffic, reduced efficiency and higher probability of errors:

#### 8. What status code does a successful GET request return?

200

#### 9. What status code does an unsuccessful GET request return?

404

#### 10. What status code does a successful POST request return?

200

#### 11. What status code does a successful DELETE request return?

204

## Things I want to know more about