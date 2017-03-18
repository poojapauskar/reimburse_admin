# Add trip details

    GET request
    https://reimburse.herokuapp.com/add_trip_details/

## Description
To add trip details

***

## HEADERS

- **USER-ID**
- **DESTINATION** 
- **START-DATE** 
- **END-DATE**
- **CATEGORY**
- **DESCRIPTION**
- **MODE-OF-TRAVEL** 
- **TRAVEL-AMOUNT** 
- **TRAVEL-DAY** 
- **TRAVEL-DATE**
- **TRAVEL-MODE-OF-PAYMENT**
- **TRAVEL-IMAGE-ID**
- **TRAVEL-DESCRIPTION**
- **HOTEL**
- **FOOD-AMOUNT** 
- **FOOD-DAY** 
- **FOOD-DATE**
- **FOOD-MODE-OF-PAYMENT**
- **FOOD-IMAGE-ID**
- **FOOD-DESCRIPTION**
- **PLACE**
- **STAY-AMOUNT** 
- **STAY-DAY** 
- **STAY-DATE**
- **STAY-MODE-OF-PAYMENT**
- **STAY-IMAGE-ID**
- **STAY-DESCRIPTION**
- **OTHERS-DESCRIPTION**
- **OTHERS-AMOUNT** 
- **OTHERS-DAY** 
- **OTHERS-DATE**
- **OTHERS-MODE-OF-PAYMENT**
- **OTHERS-IMAGE-ID**
    
***

## Output

- status: 200
- message : New Trip Added

***

## Example Input

- **USER-ID** — 1
- **DESTINATION** — Bangalore
- **START-DATE** — 20/2/2010
- **END-DATE** — 25/2/2010
- **CATEGORY** — Marketing
- **DESCRIPTION** — Business trip
- **MODE-OF-TRAVEL** — Car,Bus
- **TRAVEL-AMOUNT** — 200,100
- **TRAVEL-DAY** — 1,2
- **TRAVEL-DATE** — 20/2/2010,21/2/2010
- **TRAVEL-MODE-OF-PAYMENT** — cash,paytm
- **TRAVEL-IMAGE-ID** — 1,3
- **TRAVEL-DESCRIPTION** — business,meeting (empty string separated by commas if no description)
- **HOTEL** — Pai,New Hotel
- **FOOD-AMOUNT** — 100,500
- **FOOD-DAY** — 2,3
- **FOOD-DATE** — 21/2/2010,22/2/2010
- **FOOD-MODE-OF-PAYMENT** — cash,cash
- **FOOD-IMAGE-ID** — 5,8
- **FOOD-DESCRIPTION** — veg,non-veg
- **PLACE** — gurgaon,brigade
- **STAY-AMOUNT** — 500,2000
- **STAY-DAY** — 1,2
- **STAY-DATE** — 20/2/2010,21/2/2010
- **STAY-MODE-OF-PAYMENT** — cash,paytm
- **STAY-IMAGE-ID** — 10,12
- **STAY-DESCRIPTION** — (empty string separated by commas if no description)
- **OTHERS-DESCRIPTION** — business products,sales (empty string separated by commas if no description)
- **OTHERS-AMOUNT** — 200,300
- **OTHERS-DAY** — 1,2
- **OTHERS-DATE** — 20/2/2010,21/2/2010
- **OTHERS-MODE-OF-PAYMENT** — cah,cash
- **OTHERS-IMAGE-ID** — 34,35
