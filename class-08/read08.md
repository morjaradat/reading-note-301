# API Design Best Practices

1- What does REST stand for?

- Representational State Transfer

2- REST APIs are designed around a __2000__.

3- What is an identifer of a resource? Give an example.

- A resource has an identifier, which is a URI that uniquely identifies that resource.
example : https://adventure-works.com/orders/1

4- What are the most common HTTP verbs?

-most common REST implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

5- What should the URIs be based on?

- URIs should be based on nouns

6- Give an example of a good URI.

- https://adventure-works.com/orders 

7- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- web APIs that expose a large number of small resources ,Its bad

8- What status code does a successful GET request return?

- HTTP status code 200 (OK)

9- What status code does an unsuccessful GET request return?

- return 404 (Not Found)

10- What status code does a successful POST request return?

- returns HTTP status code 201 (Created).

11- What status code does a successful DELETE request return?

- the web server should respond with HTTP status code 204
