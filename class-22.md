# Reading 28

Reading
effects hook

What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

It let you use side effects in function components(ex:Data fetching, setting up a subscription, and manually changing the DOM in React components)

When using the useEffect Hook:


What does useEffect do?

lets react know that your component needs to do something after render and call it after performing DOM updates.

Why is useEffect called inside a component?

it lets us access the count state variable or any props right from the effect/ function

Explain the importance of properly implementing effects with Cleanup

to prevent memory leaks.

Reflection
What are your learning goals after reading and reviewing the class README?

Be well versed  in using componentWillMount, componentWillUnmount and useEffect and hooks in general.