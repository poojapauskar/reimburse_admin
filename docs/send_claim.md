# Send Claim

    GET request
    https://reimburse.herokuapp.com/send_claim/

## Description
To send claim

***

## HEADERS

- TRIP-ID : pk field of trip added
    
***

## Output

- pdf file which contains profile details, trip details and images of bills uploaded.

Response Header
- Link : <link to approve the trip>

When the link is opened ,the trip gets approved.
If the token is incorrect, it displays "Token Mismatch".
If the trip is already approved before, it displays "Link Expired".

***
