# Update Email/Phone

    POST request
    https://reimburse.herokuapp.com/update_phone_email/

## Description
To update email/phone

***

## HEADERS

- Content-Type : application/json;charset=UTF-8

***

## Input fields

Raw Json Data<br />
{<br />
 	"mobile" : "",<br />
 	"email" : ""<br />
}
    
***

## Output

1. If email and phone is same as some other users phone and email
- status - 400
- message -Already present in our database: Phone and email cannot be updated

2. If email is same as some other users email
- status - 400
- message -Already present in our database: Email cannot be updated.

3. If phone is same as some other users phone
- status - 400
- message -Already present in our database: Phone cannot be updated.

4. If new email and phone is same as the current email and phone of the user
- status - 200
- message -Already updated

5. If new email and mobile does not exists in database
- status - 200
- message -Phone and Email updated
new OTP is sent to the updated mobile and email

6. If email is new and phone is same as current phone of the user
- status - 200
- message -Phone updated
new OTP is sent to the updated mobile and email

7. If phone is new and email is same as current email of the user
- status - 200
- message -Email updated
new OTP is sent to the updated mobile and email

***
