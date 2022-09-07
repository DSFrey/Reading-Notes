# CRUD

## Status Codes Based On REST Methods

1. Status codes:

    - 100s = informational; tells the client the request has been received
    - 200s = success codes
    - 300s = redirection codes
    - 400s = client error codes - something about the request was wrong
    - 500s = server error codes

2. 202 Accepted - the request was valid, but its processing will finish sometime in the future.

3. 308 Permanent Redirect go to another URL and don't use this URL again

4. 204 No Content

5. 410 Gone

6. The client is denied access and updating authentication will not change this

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. The URL will be different in local testing than when it is deployed.

2. Middleware is code that runs when the server gets a request but before it is passed to a route.

3. It lets the server accept json as an input

4. It is a parameter

5. Patch only updates what you send it, put updates everything

6. Give the object a property called default

7. There was an error in the server

8. 200 is a generic "It was successful" and 201 is the more specific "It was created successfully"
