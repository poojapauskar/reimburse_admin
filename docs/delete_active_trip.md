# To delete an Active Trip

    POST request
    https://reimburse.herokuapp.com/delete_active_trip/

## Description
To delete an active trip

***

## HEADERS

- Content-Type : application/json;

***

## Input fields

Raw Json Data<br />
{<br />
&nbsp;	"trip_id" : "1",<br />
}<br />
    
***

## Output

{<br />
  "status": 200,<br />
  "message": "Active Trip Deleted"<br />
}<br />

***
