<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
Middleware: software that acts as a bridge between your OS or database and an application.

Express Sessions: Sessions let you persist information about a user, which helps, for example, to stay logged in when you might refresh a page.

bcrypt: a password hashing function that is resistant to rainbow-table attacks and brute-force attacks.

JWT: a compact and secure way of transmitting info between parties as JSON objects. It can be trusted because it is digitally signed via secret or public/private key-pair.

2.  What does bcrypt do in order to prevent attacks?
It increases the cost for hackers, often times by adding parameters. One such cost is time, so instead of being able to try millions of passwords in a matter of minutes, it might take days, years, or centuries!

3.  What are the three parts of the JSON Web Token?
Header.payload.signature

