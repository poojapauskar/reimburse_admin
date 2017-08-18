# To edit an Active Trip

    POST request
    https://reimburse.herokuapp.com/edit_active_trip/

## Description
To edit an active trip

***

## HEADERS

- Content-Type : application/json;

***

## Input fields

Raw Json Data<br />
{<br />
&nbsp;	"trip_id" : "1",<br />
&nbsp;	"location" : "Bangalore",<br />
&nbsp;	"start_date" : "22/11/2017",<br />
&nbsp;	"end_date" : "25/11/2017",<br />
&nbsp;	"category" : "Busines trip",<br />
&nbsp;	"description" : "busines"<br />
}<br />
    
***

## Output

{<br />
  "status": 200,<br />
  "message": "Active Trip Updated"<br />
}<br />

***
