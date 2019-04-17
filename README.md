# simple-jwt
A simple node api that uses jwt

jwt - jsonwebtoken

download and run 'npm install' to install dependencies 

The protected route is 'api/posts'

To run 'nodemon server.js'

Server.js is the entry point to this node application.

to access 'api/posts'first run this endpoint in postman firt --> 'api/login'

this will return token for you

copy the token without the quotes and add to the headers like so 

Authorization:  Bearer **token**

NB: whitespace between 'Bearer' and the 'token'

the try the 'api/posts' enpoint to get user details.

Cheers.
