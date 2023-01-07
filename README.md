# hall-Booking 
 
 GET : // To get all Room Data 
 https://hall-booking-m0e5jbuxh-gkavin57.vercel.app/
 
 
 GET : //To get booked customer details
 https://hall-booking-m0e5jbuxh-gkavin57.vercel.app/booked-customer-details
 
 
 GET : //To get booked room details 
 https://hall-booking-m0e5jbuxh-gkavin57.vercel.app/booked-room-details 
  
 POST : // To creaate a room
 https://hall-booking-m0e5jbuxh-gkavin57.vercel.app/create-room 
  
 Bodyraw (json) json :

{ "name": "medium", "seats": 40, " roomId": "003", "amenities": [ "internet_access", "food", "ac", "tv" ], 
"price": 750, "BookingStatus": "Occupied", "customerDetails": 
{ "cutstomerName": "Thala", "date": "2022-10-05", "start": "16:00", "end": "21:00", "roomId": "003", "status": "Booked" } }
 
 

POST : //To book a room 
https://hall-booking-m0e5jbuxh-gkavin57.vercel.app/room-booking 
Bodyraw (json) json :

{ "customerName" : "Super Star", "date" : "2022-10-05", "start" : "16:00", "end" : "21:00", "roomId" : "002"

}
