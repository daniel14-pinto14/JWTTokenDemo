# JWTTokenDemo using Spring.

Spring authetication with dummy username and Jwt token creation.

Steps:
a)  dummy username & pwd : admin , password.
b) Postman or yarc client extension on chrome extension on browser (Any rest API testing tools)
c) http://localhost:8080/autheticate.  pass in the body --> post method
{
   "username" : "admin",
   "paswword" : "password"

}

it will spit out the jwt token created.

4)http://localhost:8080/ ( Get method)
In header section --> custom header -> authorisation.
Bearer <jwttoken>

welcome page would be printed after verification of the request. 
