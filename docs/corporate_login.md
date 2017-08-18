# Login

    GET request
    https://reimburse.herokuapp.com/corporate_login/ 

## Description
To login a corporate user

***

## Headers

- **USERNAME** _(required)_ 
- **PASSWORD** _(required)_ 
    
***

## Output

- status 200 and message "User exists", along with the user details and access token
- status 400 and message "User does not exists"

***