# Verify

    GET request
    https://reimburse.herokuapp.com/verify/ 

## Description
To verify OTP

***

## Headers

- **mobile or email** _(required)_
- **OTP** _(required)_
    
***

## Output

- if valid then access token is returned and is_valid=1
- if invalid then access token ="" and is_valid=0

***
