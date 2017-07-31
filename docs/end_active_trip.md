# To end an Active Trip

    POST request
    https://reimburse.herokuapp.com/end_active_trip/

## Description
To end an Active Trip

***

## HEADERS

- Content-Type : application/json;

***

## Input fields

Raw Json Data<br />
{<br />
&nbsp;	"trip_id" : "1",<br />
&nbsp;	"itinerary" : [<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;			{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"name" : "Pai",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"amount" : "50.00",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"date" : "22/11/2018",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"category" : "food",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"description" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"image_id" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"job_id" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"mode_of_payment" : ""<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;			},<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;			{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"name" : "Hotel",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"amount" : "300.00",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"date" : "22/11/2018",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"category" : "stay",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"description" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"image_id" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"job_id" : "",<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;				"mode_of_payment" : "cash"<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;			}<br />
&nbsp;	 ]<br />
&nbsp;	}<br />
    
***

## Output

{<br />
  "status": 200,<br />
  "pk":trip_id,
  "message": "Trip Ended"<br />
}<br />

***
