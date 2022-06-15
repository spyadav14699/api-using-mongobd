# A restful api using express and mongodb



# User guide


 $ git clone

 $ nodemon server.js


Open this app on localhost:3000/products


For the authentication

 Use the route localhost:3000/user/sighup

 Make the post request

With the details of username, password, email, usertype

Agin make the post request on localhost:3000/user/login


Details should be provided username, password

So I used jwt so it will generate a web token


Open get request on products route

And past it on barrertoken

You will get your data.

I created a checkauth middlware past it wherever you want

So if user tipe is admin he can send the update request, deleted request and 
Many more things





