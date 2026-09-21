# Car Rental Fleet Manager
---

## Team Members

| Name             | Registration Number |
| ---------------- | ------------------- |
| K D Surya Varman | 2620030238          |
| Dhruv S Shah     | 2620030259          |

---

## Supervisor

**Mr. K. Rakesh**

---

## Abstract

The **Car Rental Fleet Manager** is a Java-based application designed to manage the operations of a car rental service. The system allows users to maintain a record of vehicles, manage customer information, handle car rentals and returns, and track vehicle availability.

The project demonstrates the practical use of **Java programming and Object-Oriented Programming (OOP)** concepts such as classes, objects, encapsulation, methods, constructors, inheritance, and polymorphism. By organizing the system into separate components for cars, customers, and rental transactions, the application provides a structured approach to managing a rental fleet.

The main objective of the project is to create a simple and efficient system that reduces manual management and demonstrates how Java can be used to build a real-world management application.

---

## Project Working Principles

The Car Rental Fleet Manager operates through a set of interconnected modules that manage the complete rental process.

### 1. Vehicle Registration

The administrator can register vehicles in the system by entering details such as:

* Vehicle ID
* Vehicle model and brand
* Registration number
* Vehicle type
* Rental price
* Current status

Each vehicle is assigned a unique identifier for easy tracking.

### 2. Vehicle Availability Management

Every vehicle has a status such as:

* **Available** – ready to be rented
* **Rented** – currently assigned to a customer
* **Under Maintenance** – unavailable due to servicing
* **Reserved** – booked for a future rental

The system updates the vehicle status whenever its rental condition changes.

### 3. Customer Management

Customer information is stored in the system, including details such as:

* Customer ID
* Name
* Contact information
* Driving licence details
* Rental history

This allows the administrator to identify customers and associate them with their rentals.

### 4. Rental Booking

When a customer requests a vehicle, the system checks whether the selected vehicle is available. If available, a rental record is created containing:

* Customer details
* Vehicle details
* Rental date
* Return date
* Rental duration

The vehicle is then marked as **Rented** or **Reserved**, depending on the booking.

### 5. Rental Cost Calculation

The system calculates the rental cost based on the vehicle's rental rate and rental duration.

**Rental Cost = Daily Rental Rate × Number of Rental Days**

Additional charges such as late-return fees or other applicable charges can also be incorporated.

### 6. Vehicle Return

When the customer returns the vehicle, the system records the return and calculates the final rental amount. The vehicle status is then changed back to **Available**, unless maintenance is required.

### 7. Maintenance Management

Vehicles requiring servicing can be marked as **Under Maintenance**. Such vehicles cannot be assigned to new customers until their maintenance status is cleared.

The system can maintain maintenance records such as service date, maintenance type, and associated cost.

### 8. Booking Validation

Before confirming a rental, the system validates:

* Whether the vehicle exists
* Whether the vehicle is available
* Whether the customer exists
* Whether the rental dates are valid
* Whether the requested vehicle is already reserved

This prevents invalid or conflicting bookings.

### 9. Data Storage and Retrieval

Vehicle, customer, rental, and maintenance information is stored using appropriate data structures or persistent storage such as files or a database. The system retrieves this information whenever an administrator needs to view or update records.

### 10. Fleet Monitoring

The administrator can view the current state of the entire fleet and identify:

* Available vehicles
* Currently rented vehicles
* Reserved vehicles
* Vehicles under maintenance

This provides an overview of fleet utilization.

### 11. Record Updating

Whenever an operation is completed, the relevant records are updated. For example, completing a rental changes the vehicle from **Rented → Available**, while sending a vehicle for servicing changes it from **Available → Under Maintenance**.

### 12. Error Handling and Validation

The system checks user inputs and prevents invalid operations such as:

* Renting an unavailable vehicle
* Entering invalid vehicle or customer IDs
* Creating duplicate records
* Returning a vehicle that is not currently rented
* Entering invalid rental dates

### 13. Reporting

The system can generate basic information about fleet operations, such as rental history, vehicle availability, maintenance records, and revenue generated from rentals.

### Overall Working Flow

**Admin → Vehicle/Customer Registration → Vehicle Availability Check → Booking → Rental → Return → Cost Calculation → Vehicle Status Update → Record Storage**

This workflow ensures that vehicle availability, customer information, bookings, rentals, and maintenance records remain synchronized throughout the operation of the system.


---

## Current Phase Status

* [x] Project Idea Finalized
* [x] Requirement Analysis
* [ ] Design Phase
* [ ] Development Phase
* [ ] Testing Phase
* [ ] Final Submission

---

