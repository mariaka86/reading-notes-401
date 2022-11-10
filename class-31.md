# Reading 39

What concerns are addressed by Redux Toolkit?

- configuring a redux store simpler
- decreasing the packages needed to be installed to do anything useful in redux
- decreasing boilerplate code required

What does configureStore() do?

wraps createStore, provides simplified configurations and good defaults. It also automatically combines your slice reducers and adds on all the redux middleware you supply.

How would I use createSlice()?

By creating a reducer function object, a slice name and an initial state value. This will automatically generate a slice reducer along with action creators and action types(to auto generate slice reducers)

MobX

What is Mobx?

a management solution

How does MobX make it “impossible” to produce an inconsistent state?

by making everything that can be derived from app state become derived automatically

How would we build a reactive user interface?

by using packages that keep components in sync with state
Tutorial

What take-away(s) did this tutorial provide?