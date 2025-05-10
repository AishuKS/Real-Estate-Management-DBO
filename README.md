# Real Estate Management Application

A full-stack real estate management system designed and developed as part of the CS 425 Database Organization course (Spring 2025). This application supports property listing, booking, and management for both agents and renters, including features such as user registration, reward points, and neighborhood insights.

## Features
User Management
- Register as Agent or Renter
- Maintain profile details and multiple addresses
- Renters can store and manage multiple credit cards
- Agents can manage property listings

Property Management
- Agents can add/update/delete properties
- Each property is linked with an address and neighborhood info
- Stores attributes such as type, price, availability, rooms, square footage, and more

Search & Booking
- Renters can search properties by:
  * Location, type, availability, budget, rooms
- Properties shown based on filters and sorted by price or number of rooms
- Booking system allows renters to:
  * Select rental dates
  * Choose a payment method
  * See total cost and booking details
- Support for cancellations with refund and fees

Neighborhood Insights
- Crime rate and nearby schools stored for each neighborhood

Reward Program
- Renters earn reward points equal to rental price after each booking

## Database Schema
SQL schema includes the following tables (with constraints and indexes):
- User, Renter, Agent
- Address, CreditCard, Reward
- Property, Booking, Neighborhood

Technologies Used
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: PostgreSQL
- ORM/Query: Raw SQL with index optimization
- Hosting: Localhost or any preferred deployment service
- Tools: pgAdmin, VS Code, Git
