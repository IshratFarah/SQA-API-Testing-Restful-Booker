# SQA-API-Testing-Restful-Booker

### Auth

- Validate header.
- Validate response code and response message.
- Validate token generation using valid and invalid credentials.
- Validate data type of token.

### GetBookingIds

- Validate response code and response message.
- Validate absence of duplicate Ids.
- Validate searching with 'Firstname' only as optional parameter.
- Validate searching with 'Lastname' only as optional parameter.
- Validate searching with 'Firstname' and 'Lastname' as optional parameter.
- Validate searching with 'Firstname', 'Lastname', 'Checkin' and 'Checkout' as optional parameter.


### GetBooking

- Validate header.
- Validate response code and response message.
- Validate schema of response body.
- Validate searching with invalid Id.
- Validate all field values.

### CreateBooking

- Validate header.
- Validate response code and response message.
- Validate creation of booking with invalid data type in every field.
- Validate creation of booking with valid data.

### UpdateBooking
- Validate updating all fields with valid values.
- Validate updating all fields with invalid values.
- Validate forbidance of partial updating.

### PartialUpdateBooking
- Validate updating some fields (partial update).
- Validate updating all fields.
- Validate partial updating with invalid field values.

### DeleteBooking
- Validate deleting a booking without sending any ID.
- Validate deleting a booking with an invalid ID.
- Validate deleting a booking with valid ID.
- Validate deleting a booking twice.

### Ping
- Validate response code and response message.
  
