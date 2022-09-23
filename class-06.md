# Class 06 readings



Explain to a non-technical friend how you would safely hash and store a password.

hashing, is basically concealing your passwords in a database and making sure they don't appear in plain text using an algorithm

What is Bcrypt?

an algorithm that make hash attacks more difficult.

Why might you use something like Bcrypt?

to protect your passwords and make them more secure


Basic Auth

What is Basic Authentication?

it's a method for a web browser that provides a user name and password whenever a request is made.

What properties are necessary in the header of a Basic Auth request?

the credential to authenticate a user agent with a server (username and password)


How are username:password in Basic Auth encoded?

they're encoded in Base64


OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter.

The process of verifying that an person, website or entity is who they say they are.


How should your error messaging respond (both HTTP and HTML)? Why?

in a generic error message, in case there's an attack and it migh leak information about a valid account


Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.