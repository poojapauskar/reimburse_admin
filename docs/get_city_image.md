# Get city image

    GET request
    https://reimburse.herokuapp.com/get_place_image/

## Description
To get the image of a particular city

***

## HEADERS

- PK : <pk field of the city>
- IMAGE-TYPE : <thumbnail, medium, large>

***

## Output

On success<br />
{<br />
    "status": 200,<br />
    "image_link": "http://res.cloudinary.com/hzplhn0co/image/upload/w_75,h_100/smartally/id232944.jpg",<br />
    "message": "Image found"<br />
}<br />
<br />
On Failure<br />
{<br />
    "status": 400,<br />
    "image_link": "http://res.cloudinary.com/hzplhn0co/image/upload/w_75,h_100/smartally/id232944.jpg",<br />
    "message": "No Image found"<br />
}<br />

***
