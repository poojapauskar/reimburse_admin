# Mark Trip as Reimbursed

    GET request
    https://reimburse.herokuapp.com/mark_trip_as_reimbursed/

## Description
To set trip status

***

## Headers 

- **TRIP-ID** — pk field of trip
- **STATUS** — reimbursed, rejected, completed, archived
    
***

## Output

{<br />
    "status": 200,<br />
    'Trip Status':"reimbursed",<br />
}<br />

***
