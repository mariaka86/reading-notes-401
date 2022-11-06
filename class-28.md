# Reading 36

Dan Abramov Redux Tutorials

What is the first principle of Redux?

- single source of truth
- state is read only
- changes are made with pure functions

what is a store and what do we use our reducers for within that store?

- Reducer, functions that take the current state and action as argument and generate a new state

(state, action) => newState.

It brings together the state, reducers and  actions that makeup your app. A redux reducer has a root reducer function that is responsible for handling all of the actions that are siapached and creating a new state everytime

Name three Redux store methods given to us by createStore and describe their use.

- getState, helps you retrieve current state of redux store

- dispatch, it allow you to dispatch an action to change a state in your application

- subscribe, helps register a callback that store will call when action has been dispatched and as soon as state has update the view will re-render automatically.

Explain to a non-technical recruiter what combineReducers() does and why it is useful.

It's a helper function that turns an object that has differing reducing functions into a single reducing function.

It's usefule because it you can then pass the function in createStore.

Additional Questions

Looking ahead at this module’s course schedule, What do you look forward to learning?

Learning react native

What are your learning goals after reading and reviewing the class README? 

contribute to open source.
