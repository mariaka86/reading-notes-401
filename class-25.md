# Reading 32

Hooks and Context example

With regard to the React Context API, what does a “provider” do?

- it's responsible for displayint the local state of snackbars(alerts)
- it also exposes an APi for globally managing them

With regard to the React Context API, how would we implement a “consumer” role?

by using a custom hook that acts as a small wrapper around the useContext react hook which consumes new context

Specifically with Context, how are we “wrapping” components to achieve our goals?

The context that the provider is producing, by using the useContext react hook

Awesome React Context links

Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:

Takeaway 1: There are plenty of libraries that act as small wrappers around React Context API

Takeaway 2:The provider component is used high in the tree and accepts a prop called value

- consumer component is used anywhere below the tree and accepts a prop called children

Reflection
What are your learning goals after reading and reviewing the class README?

Be able to navigate my way through context.