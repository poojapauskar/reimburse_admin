# To post an Active Trip

    POST request
    https://reimburse.herokuapp.com/post_active_trips/

## Description
To post an active trip

***

## HEADERS

- Content-Type : application/json;

***

## Input fields

Raw Json Data<br />
{<br />
&nbsp;	"user_id" : "pk fields of open acnt user/organiztion user",<br />
&nbsp;	"location" : "Bangalore",<br />
&nbsp;	"start_date" : "22/11/2017",<br />
&nbsp;	"end_date" : "",<br />
&nbsp;	"category" : "Busines trip",<br />
&nbsp;	"description" : "busines"<br />
&nbsp;	"account_token" : "account_token"<br />
}<br />
    
***

## Output

{<br />
  "status": 200,<br />
  "pk":trip_id,<br />
  "message": "New Trip Added"<br />
}<br />

***
