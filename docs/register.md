# Register

    POST request
    https://reimburse.herokuapp.com/register/ 

## Description
To register a user

***

## Input Fields

- **mobile** _(required)_ — Either mobile or email required
- **email** _(required)_ — Either mobile or email required
- **name** _(required)_
- **username**
- **password**
- **is_admin**
- **company**
- **age**
- **otp**
- **is_valid**
- **access_token** 
    
***

## Output

- Otp is mailed or messaged.
- default 444444 can b used.
- pk field is present only if new user

***
