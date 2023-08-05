# Booking_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run API_Testing_101.postman_collection.json -e ENV_101.postman_environment.json
```
- Run Command for Report: 
```console 
newman run API_Testing_101.postman_collection.json -e ENV_101.postman_environment.json -r cli,htmlextra
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
1. ### Create Booking
	> Create Data Sets Using the Dynamic Random Variables.

2. ### (Get Booking) Verify Crated Booking Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > Date of Birth
   4. > Totalprice
   5. > Depositpaid
   6. > Checkin date

3. ### Update Booking
	> In the test case you need to validate the following field values:
 	1. > Only status code
     
4. ### (Get updated Booking) Verify Updated Student Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > Date of Birth
   4. > Totalprice
   5. > Depositpaid
   6. > Checkin date

5. ### Delete Booking
	> In the test case you need to validate the following field values:
	1. > Only Message

## Newman Report Summary:
![Newman Report Summary](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/39287503-29ac-469a-bfaa-bc4a52be8416)
)

![Newman Report Summary](https://github.com/jasin0x/Booking_Rest_API_Newman/assets/46416678/0ed33abe-6d60-4525-bcf9-c443284bceb1)
