# Guide line for rest api for web

## API list
- [Guide line for rest api for web](#guide-line-for-rest-api-for-web)
  - [API list](#api-list)
    - [Login](#login)
      - [/login](#login-1)
    - [User](#user)
      - [/user](#user-1)
      - [/user/{id}](#userid)

### Login
#### /login  
    1. Request
       1. metod: POST
       2. URL : localhost:8080/login
       3. parmeters: 
          1. id (long)
          2. password (encrypted)
    2. Response : json
       1. 200
       {
           code: 200
           data: {
               userID : testID
               userName : tsetName
           }
        }
        1. 404
        {
            code : 404
            message : "Fail to login"
        }
            

### User
#### /user ####
    1. Request
       1. metod: GET
       2. URL : localhost:8080/user/{id}
    2. Response : json
       1. 200
       {
           code: 200
           data: {
               userID : testID1
               userName : tsetName1
           },{
               userID : testID2
               userName : tsetName2
           }
        }
        2. 404
        {
            code : 404
            message : "User(s) not found"
        }
#### /user/{id} ####
    1. Request
       1. metod: GET
       2. URL : localhost:8080/user/{id}
       3. parmeters: 
          1. id (long)
    2. Response : json
       1. 200
       {
           code: 200
           data: {
               userID : testID
               userName : tsetName
           }
        }
        2. 404
        {
            code : 404
            message : "User not found"
        }
