# JWTTokenDemo using Spring.

Spring authetication with dummy username and Jwt token creation.

Steps:

a)  Dummy username & pwd : admin , password.

b)  Postman or yarc client extension on chrome extension on browser (Any rest API testing tools)


c) http://localhost:8080/autheticate.  pass in the body --> post method

{

   "username" : "admin",
   
   "paswword" : "password"


}

it will print  out the jwt token created in response

4)http://localhost:8080/ ( Get method)

In header section --> custom header -> authorisation.
Bearer+(space)+jwttoken printed in the previous request

welcome page would be printed after verification of the request in the body.
