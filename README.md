# CollegeRoomScheduler-
Java GUI that uses Derby Database Tables. Faculty at a college/institution can reserve a room or be waitlisted based on room availability and number of seats.   

Application features knowledge of implementing a relational database engine, Java OOP and GUI design, and SQL. 

RoomScheduler features many functionalities to accomadate for all scenarios when scheduling:
1. Add Faculty by Name
2. Place Reservation by Faculty name, date, and seats required
3. Add date to database
4. Check reservations by date 
5. Check reservations by Faculty name 
6. Check entire waitlist 
7. Check waitlist by date or faculty
8. Add a room by room # and seating capacity or drop a room by room # drom database
9. Cancel Reservation
10. Clear entire database (For testing purposes)

Every function that is made available to the user is dynamic. If someone drops their reservation, the database will automatically check the waitlist to see if
someone else can fill their spot. If a room is dropped, reservations and waitlisted users will be adjusted accordingly. etc. 

The application uses Apache Derby Database 10.14.2.0

Repository includes: zip of code (RoomSchedulerTylertfm5291.zip)
                 and zip of database (RoomSchedulerDBTylertfm5291.zip) 
