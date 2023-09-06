# Booking_Rest_API_Postman & Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Rest_Booking_API.postman_collection.json -e Rest_Booking_API_ENV.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Rest_Booking_API.postman_collection.json -e Rest_Booking_API_ENV.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- [https://documenter.getpostman.com/view/13082503/2s93Xwz4Az](https://documenter.getpostman.com/view/28914312/2s9XxyRDsN#28baaf7f-5ea0-473e-9815-b37845fd62ca)

## Test case list:
1. ### Get Booking Ids
   	> In the test case you need to validate the following field values:
   	1. > Status code

2. ### Create Booking
   	> Create Data Sets Using the Dynamic Random Variables and verify the follwings:
   	1. > Status coode
   	2. > Body string
   	3. > Content Type
   	4. > Respose time

3. ### (Get Booking) Verify Crated Booking Details
	> In the test case you need to validate the following field values:
 	1. > Status Code
 	2. > First Name
 	3. > Last Name
   	4. > Totalprice
   	5. > Depositpaid
   	6. > Checkin date
   	7. > Checkout date
   	8. > Json schema

4. ### Token Generator
	> In the test case you need to validate the following field vlaues:
 	1. > Status Code
    	2. > Check if token is present

5. ### Update Partial Booking
	> In the test case you need to validate the following field values:
 	1. > Status code
     
6. ### (Get partial updated Booking) Verify partial Updated Booking Details
	> In the test case you need to validate the following field values:
 	1. > Status Code
 	2. > First Name
 	3. > Last Name
 	4. > Totalprice
	5. > Depositpaid

7. ### Update Full Booking
   	> Create Data Sets Using the Dynamic Random Variables and verify the follwings:
 	1. > Status coode
   	2. > Body string
  	3. > Content Type
  	4. > Respose time
     
8. ### (Get fully updated Booking) Verify fully Updated Booking Details
	> In the test case you need to validate the following field values:
 	1. > Status Code
 	2. > First Name
 	3. > Last Name
   	4. > Totalprice
   	5. > Depositpaid
  	6. > Checkin date
   	7. > Checkout date
  	8. > Json schema

9. ### Delete Booking
	> In the test case you need to validate the following field values:
 	1. > Status code
	2. > Message.
    
##   Negative test case

10. ### Get booking details invalid ID
    > In the test case you need to validate the following field values:
 	1. > Status code

12. ### Create booking invalid character
	> In the test case you need to validate the following field values:
 	1. > Status code

## Newman Report Summary:
![Newman Report Summary](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/44a96c57-38a3-411e-9154-b7162f163dc3)

![Newman Report Summary](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/1429318a-7f43-41e6-ae36-f39f8f4911dd)

## Performance Test using postman

   > Virtual User: 100,
   > Duration: 180 Seconds,
   > Ramp up period: 60 Seconds 

### Performance graph

![image](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/5cc0d952-c837-4e69-bad3-844e18725948)

### Performance details for total duration 

![image](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/2f8f86e2-6fce-49c5-865c-bc42e03a3df3)

