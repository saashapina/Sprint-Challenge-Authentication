<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    Middleware, local and global, is software that runs between req and res. 

    A Session is a place to store data that you want access to across requests. Each user that visits your website has a unique session. You can use sessions to store and access user data as they browse your application.

    Bcrypt is a password hashing algorithm. Its slowness, multiple rounds, and use of Salts ensure that an attacker must spend a LOT more time to be able to crack your passwords.

    JWT is a JSON Web Token, its used to represent whether or not a request is authenticated

2.  What does bcrypt do in order to prevent attacks?
    What bcrypt does to prevent attacks is hash the password, it does this by appending random characters and numbers to the end of the password. It has functionality to prevent attacks by increasing the amount of time to hash a password.
3.  What are the three parts of the JSON Web Token?
    Three parts of the JSON Web Token is the Header, the Payload, and the Signature
