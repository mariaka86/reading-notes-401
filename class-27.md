# Reading 34

Explain the different between a query string parameter and a path parameter.

- path parameter describes location of the resource
- query string parameter are used to filter and sort resources

What would our API URL with a path id parameter be given the following information:
Domain: <http://our-site.com>
v3
model name: stuff
id: things

http:http://our-site.com:stuff/v3/things. 

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

Review Auth Server Build

Describe how you would use middleware to implement basic and bearer auth.

- basic auth would include the username and password 
- bearer auth would be a token to be used on any route that requires a user to be signed in.

Describe the handshake necessary to implement OAuth.

Step 1 – The User Shows Intent.
Step 2 – The Consumer Gets Permission.
Step 3 – The User Is Redirected to the Service Provider.
Step 4 – The User Gives Permission.
Step 5 – The Consumer Obtains an Access Token.
Step 6 – The Consumer Accesses the Protected Resource.


Describe how Role Based Access Control works to a non-technical friend.

Role Based Access Control is basically assigning what a person/ user can or can't do base on what their role is.

Reflection
What are your learning goals after reading and reviewing the class README?

Get good at hashmaps/ datastructures and algorithms
