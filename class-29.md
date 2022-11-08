# Reading 37

Reading
Multiple Reducers Example

Why create multiple reducers?

to make code much more readable (ie make it easier to break up into seperate files)

How would you combine multiple reducers?

using the combineReducers function

How will you manage state as an immutable object? why?

by destructuring,copying state and overwriting the value that needs to be changed.

Redux Docs: Using Combined Reducers

combineReducers is a utility function to simplify the most common use case when writing ___ _____ .

Redux Reducers

Explain how combineReducers assembles the new state tree.

combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed

How would you define initial state in an app using combineReducers?

There are two ways to define it 

- First, the createStore function can take preloadedState as its second argument
- Second is for the root reducer to return the initial state value when the state argument is undefined.



Redux Docs: Combined Reducer Syntax

Why will you want to split your reducing functions as your app becomes more complex?

so you can manage independant parts of state

The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

combineReducers , createStore

What is a popular convention when naming reducers?

to name reducers after the state slices they manage


Reflection
What are your learning goals after reading and reviewing the class README?

be able to apply what i've learned to my labs and in real life.