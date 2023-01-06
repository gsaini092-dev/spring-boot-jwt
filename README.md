# spring-boot-jwt
JWT Token Example

1. Generate Token using POST call
   URL: ```localhost:8080/authenticate```
   
   Payload:
   ```
   {
   "username" : "javainuse",
   "password" : "password"
   }
   ```
   
2. Use token to access Get endpoint:
  URL: ```localhost:8080/hello```
  
  In header, use the token  as 
  Bearer <TOKEN GENERATED in step 1>
