# Edit Profile

    POST request
    https://reimburse.herokuapp.com/myprofile_update/?access_token=<user access token>

## Description
To edit my profile

***

## HEADERS

- Content-Type : application/json;charset=UTF-8

***

## Input fields

Raw Json Data<br />
{  
   "name":"",<br />
   "company":"",<br />
   "gender":"",<br />
   "age":"",<br />
   "image_id":"",<br />
   "department":""<br />
}
    
***

## Output

- status: 200
- message : Profile Updated

***
