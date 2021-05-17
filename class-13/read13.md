# Status Codes Based On REST Methods

1- In your own words, describe what each group of status code represents:

1. 100’s = its informational status codes that tell the server the requset information
2. 200’s = its success codes that tell the client that its request was accepted
3. 300’s = its redirection codes that tell the client that the resource they are requesting isn’t available at the expected location anymore
4. 400’s = its client error codes that are all about invalid requests a client sent to a server.
5. 500’s = its server error codes. Often they indicate problems with overwhelmed servers

2- What is a status code 202?

- mean This code tells the client that the request was valid, but its processing will finish sometime in the future .

3- What is a status code 308?

- This tells the client to use another URL to access the resource and not use the current URL anymore

4- What code would you use if an update didn’t return data to a client?

- code 204

5- What code would you use if a resource used to exist but no longer does?

- code 404

6- What is the ‘Forbidden’ status code?

- The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
