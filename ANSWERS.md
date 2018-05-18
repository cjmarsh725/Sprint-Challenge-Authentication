<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
Middleware are functions that run in the Middleware stack and can be used to modify the request object before later Middleware gets it. Sessions are a way to store data across requests, either in application memory or some other form of storage like a database. bcrypt is a package for cryptography with a useful method to hash strings into something that is harder for attackers to interpret. JWT stands for json web tokens and is another way to persist data in local storage.
2.  What does bcrypt do in order to prevent attacks?
The hash function is a one-way function that turns a string into a very long string. The process can not be reversed so if a password is stored this way it is hard for attackers to crack it unless they use a rainbow table of existing passwords and their hashes.
3.  What are the three parts of the JSON Web Token?
There is a header, payload, and verify signature represented by a long string for each separated by periods in the encoded token.