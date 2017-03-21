# Add Trip Details

    POST request
    https://reimburse.herokuapp.com/add_trip_details/

## Description
To add trip details

***

## HEADERS

- Content-Type : application/json;charset=UTF-8

***

## Input fields

Raw Json Data<br />
{<br />
&nbsp;	"user_id" : "1",<br />
&nbsp;	"location" : "Bangalore",<br />
&nbsp;	"start_date" : "22/11/2017",<br />
&nbsp;	"end_date" : "25/11/2017",<br />
&nbsp;	"category" : "Busines trip",<br />
&nbsp;	"description" : "busines",<br />
&nbsp;	"itinerary" : [<br />
&nbsp;			{<br />
&nbsp;&nbsp;				"name" : "Pai",<br />
&nbsp;&nbsp;				"amount" : "50.00",<br />
&nbsp;&nbsp;				"date" : "22/11/2018",<br />
&nbsp;&nbsp;				"category" : "food",<br />
&nbsp;&nbsp;				"description" : "",<br />
&nbsp;&nbsp;				"image_id" : "",<br />
&nbsp;&nbsp;				"mode_of_payment" : ""<br />
&nbsp;			},<br />
&nbsp;			{<br />
&nbsp;&nbsp;				"name" : "Hotel",<br />
&nbsp;&nbsp;				"amount" : "300.00",<br />
&nbsp;&nbsp;				"date" : "22/11/2018",<br />
&nbsp;&nbsp;				"category" : "stay",<br />
&nbsp;&nbsp;				"description" : "",<br />
&nbsp;&nbsp;				"image_id" : "",<br />
&nbsp;&nbsp;				"mode_of_payment" : "cash"<br />
&nbsp;			}<br />
&nbsp;	 ]<br />
&nbsp;	}<br />
    
***

## Output

{<br />
  "status": 200,<br />
  "message": "New Trip Added"<br />
}<br />

***
