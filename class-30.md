# Reading 38

Reading
async actions

Why use Redux middleware?

to enable writing logic with side effect

Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

a thunk function is dispatched into our middleware from an event handler which sends an API/ async call. Once the call is complete a real action object is then dispatched

How are we accommodating async in our Redux app?

By using Redux's offical version of async function middlware which is called Redux thunk middleware

thunk middleware

Why would you need redux-thunk middleware?

it allows you to return functions

Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

function

Describe how any return value from the inner thunk function will be made available.
it would be available via the next middleware in the chain


Reflection
What are your learning goals after reading and reviewing the class README?

complete my labs that include Redux this weekend