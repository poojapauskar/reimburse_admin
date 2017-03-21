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
{
	"user_id" : "1",<br />
	"location" : "Bangalore",<br />
	"start_date" : "22/11/2017",<br />
	"end_date" : "25/11/2017",<br />
	"category" : "Busines trip",<br />
	"description" : "busines",<br />
	"itinerary" : [
			{
				"name" : "Pai",<br />
				"amount" : "50.00",<br />
				"date" : "22/11/2018",<br />
				"category" : "food",<br />
				"description" : "",<br />
				"image_id" : "",<br />
				"mode_of_payment" : ""<br />
			},
			{
				"name" : "Hotel",<br />
				"amount" : "300.00",<br />
				"date" : "22/11/2018",<br />
				"category" : "stay",<br />
				"description" : "",<br />
				"image_id" : "",<br />
				"mode_of_payment" : "cash"<br />
			}
	 ]
	}
    
***

## Output

{
  "status": 200,<br />
  "message": "New Trip Added"<br />
}

***
