class 03 readings
Readings

Review: ES6 Classes

Classes are a template for creating ____.

Objects

Can a class declaration be hoisted?

No, they have to be defined before being declared

How would you describe a constructor and contextual “this” to a non-technical friend?

this refers to the property of that particular constructor

Using Express Routing

Within Express, what does routing refer to?

an app's endpoint and their responses to client requests


What is the difference between a route path and a route method?

route methods handle requests, route paths define endpoints.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter? 

When there's a another route handler that can handle the request, pass control to the next middleware function.
Express Routing

What is an Express Router?

a class that can help us create router handlers/ a mini express application

By what mean do we initialize express.Router() in an express server?

var router = express.Router();

What do we use route middleware for?

validation and error handleling.