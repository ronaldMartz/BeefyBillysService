# Beefy Billy's Ordering and Delivery Service
## Project Description

Restaurant Delivery App is a web-app designed to facilitate Customers ordering food from a restaurant online for delivery or pick up. The Customer is also able to create a reservation at the restaurant for a future date. Employees of this establishment are able to view pending orders and update the status as completed or cancelled, as well as submit new orders if the Customer orders over the phone. Employees may also view and update the list of reservations as well as make a reservation for Customers. Managers can make changes to the menu as well as see a list of all orders regardless of status. Managers can also create Employees.

## Technologies Used

-Java 1.8
-Spring WebMVC 4.3.27
-Spring Core 4.3.29
-Spring ORM 4.3.29
-Hibernate 4.3.11
-Junit
-PostgreSQL
-Spring Test 4.3.27
-Mockito
-Angular for HTML/CSS/Typescript
-Bootstrap
-AWS RDS
-Log4j
-Git and GitHub

## Features

List of features ready and TODOs for future development
-A Customer can create a New Order
-A Customer can make a New Reservation
-An Employee can login/logout
-An Employee can view and Update previous Orders and their Status
-An Employee can view and Update previous Reservations and their Status
-An Employee can create an Order for Customers
-An Employee can create a Reservation for Customers
-A Manager can login/logout
-A Manager can view all Employees registered with the service
-A Manager can register Employees to the service
-A Manager can view and Update all Orders, Reservations, and their respective Status.
-A Manager can view and Update Menu Items

To-do list:

-A Customer can login/logout (optional)
-A Customer can Save favorite orders once logged in (optional)
-A Customer can Save and Update location information (optional)
-A Manager or Employee can view the address on a map via Google Maps API (optional)

## Getting Started
   
git clone https://github.com/ronaldMartz/BeefyBillysService.git

## Usage

- When the program starts you should see https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/homePage.png

- The buttons on the bottom of the home page will take you to either the New Orders page, or New Reservation page. Both of those have corresponding links on the NavBar at the top of the page.

- Upon clicking the "Order Online" button or "New Orders" on the NavBar it will take you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/newOrder.png where you can see a menu and submit your order.

- Upon clicking the "Make a Reservation" button or "Reservations" on the NavBar it will take you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/newReservation.png where you can fill out your information and the date and time of the reservation.

- When an Employee clicks on the "Employee Login" button on the NavBar it takes them to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/login.png

- NavBar after login: https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/navBar.png

- After login the NavBar items update to show "Customer Info", "View Orders", and "Logout".

- Clicking on "Customer Info" will show https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/customerHistory.png where a table of previous customers will appear.

- Clicking on "View Orders" takes you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/orderHistory.png where all previous orders will show with their status, as well as buttons to update to "Cancelled" or "Delivered"

- Clicking on "Reservations" will show https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/employeeReservation.png which now includes a list of past and future reservations, allowing for the status to be updated here as well.

- Clicking on "Logout" will take the Employee back to the Login Page.

- When a Manager logs in, the NavBar will update to show "Manage Employees" and "Manage Menu" along with the Employee options.

- "Manage Employees" takes you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/employeePage.png which shows a list of registered Employees and allows a Manager to register additional Employees.

- "Manage Menu" takes you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/manageMenu.png which shows a list of Menu Items that can be updated using the form at the bottom, deleted by clicking on a button, or added to by clicking the "Add Menu Item" button at the top.

- The "Add Menu Item" button takes you to https://github.com/ronaldMartz/BeefyBillysService/blob/main/Images/addToMenu.png where you can set the Name of the item, Give a description, and set the Price (in whole dollars.)
