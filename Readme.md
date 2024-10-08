# NodeJS Hall Booking API Task 🏫📅

**This repository is created for NodeJS Hall Booking API Task** 


This Web application is created for managing rooms booking  in a Hall.

## Deployment

*Check out My NodeJS Hall Booking System Here*👉🏻 [![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)]()

## Endpoints with Output Screenshots

### List All the Booked Rooms: View a list of all booked rooms along with customer details and booking information.
- GET: Use the endpoint/hallapi/roominfo to get the All Room Details
  ![alt text](Screenshoot/allroominfo.png)


### Create Room: Easily create new rooms with specified details such as capacity, amenities, and price per hour.
- POST: Change the endpoint/hallapi/createroom to Create a New Room
  ![alt text](Screenshoot/Create_room.png)
  

### Book Room: Seamlessly book available rooms for specific dates and times, ensuring no double bookings.
- POST: Change the endpoint/hallapi/bookroom to Book a New Room
  ![alt text](Screenshoot/Book_room1.png)
  ![alt text](Screenshoot/Book_room2.png)
  ![alt text](Screenshoot/allready_Booked.png)

### List the Booked Rooms: Get insights into all booked rooms, including Customer Information. 
- GET: Change the endpoint/hallapi/bookedroomdata to retrieve all the Booked Room Data
  ![alt text](Screenshoot/booked_room_data.png)


### List Customers Booked Rooms Data: Get insights into all customers who have booked rooms, including their booking history.
- GET: Change the endpoint/hallapi/customersbookeddata to retrieve all the Customers Booked Room Data
  ![alt text](Screenshoot/Customer_booked_data.png)


### List Customer Booking Count: Get booking details for each customer along with booking count.
- GET: Change the endpoint/hallapi/customerbookingcount to retrieve Booking Counts and Room Data for Booked Customers
  ![alt text](Screenshoot/Customer_Booked_count.png)

## NodeJS
  - It is used for server-side programming, and primarily deployed for non-blocking, event-driven servers, such as traditional web sites and back-end API services, but was originally designed with real-time, push-based architectures in mind. Every browser has its own version of a JS engine, and node.

## ExpressJS
  - Express is a node js web application framework that provides broad features for building web and mobile applications. It is used to build a single page, multipage, and hybrid web application. It's a layer built on the top of the Node js that helps manage servers and routes.

## Programming Language Used 💡
    
  <div align="left">
  <img src="https://www.svgrepo.com/show/376337/node-js.svg" height="100" alt="nodejs logo"  />
  <img width="50" />
  </div>

  <div align="left">
  <img src="https://www.svgrepo.com/show/353724/express.svg" height="100" alt="expressjs logo"  />
  <img width="50" />
  </div>

## Programming Tool Used ⚙️

  <div align="left">
  <img src="https://www.svgrepo.com/show/354522/visual-studio-code.svg" height="100" alt="vscode logo"  />
  <img width="30" />
  </div>

## JSON Data Schema

- **Room Object Schema**

```json
{
  "room_id": 1,
  "room_name": "Diplomatic Suite",
  "room_status": "available",
  "amenities": "TV, A/C, Laundry, Jaccuzi, WiFi, Private Swimming Pool",
  "seats": 5,
  "price_per_hour": 7000
}
```

- **Booking Object Schema**

```json
{
  "roomID": 1,
  "booking_date": "12-08-2024",
  "start_time": "12:00 pm",
  "end_time": "01:00 pm",
  "booking_id": 1,
  "status": "Booked"
}
```