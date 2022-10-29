# Reading 31

Context API

What can React Context provide your app?

 a way to pass data down the componenent tree without having to pass props down manually

Why might we use Context?

If the data that is needed to be passed down will be used by many components/ for data that is considered global.

Why should we use it sparingly?

it makes component reuse difficult.

Awesome React Context links

Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:
Takeaway 1:const AuthenticatedApp = React.lazy(() => import('./authenticated-app'))
Having code in this format allows authenticated users to get to an app faster and unauthenticated users to get to the login page faster


Takeaway 2:
Deprecated functions in the new context API include
componentWillMount — use componentDidMount instead
componentWillUpdate — use componentDidUpdate instead
componentWillReceiveProps — new function, static getDerivedStateFromProps is introduced

Additional Questions

Looking ahead at this module’s course schedule, What do you look forward to learning?

What are your learning goals after reading and reviewing the class README?
