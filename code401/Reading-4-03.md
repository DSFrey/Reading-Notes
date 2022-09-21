# Express REST API

## Review: ES6 Classes

1. Classes are a template for creating objects.

2. Class declarations are effectively unable to be hoisted.

3. The constructor is a function that is used to build an object with a class. Inside this function, the keyword `this` is used to refer to the specific object being made, rather than the class in general.

## Using Express Routing

1. Routing refers to the process of defining an application's endpoints and how they respond to a client's requests.

2. A route path is where the request is being directed. A route method is the type of request being made.

3. `next` is used when a route needs to use more than one callback function. It is passed into the middleware as a parameter, then `next()` is called in the body of the function to pass it off to the next callback in line.

## Express Routing

1. >Router is like a mini-Express application. It doesn’t bring in views or settings but provides us with the routing APIs like .use, .get, .param, and route.

2. `var router = express.Router();`

3. Middleware is used to perform functions before a request is fulfilled. This may include authentication, validation, data logging, error handling, etc.
