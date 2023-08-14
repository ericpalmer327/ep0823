# Tool Rental Application (`ep0823`)

This repository contains a Spring Boot application designed to simulate a point-of-sale system for stores that rent out large tools.

## Overview

The `ep0823` application is built using the Spring Boot framework, leveraging its capabilities to create a robust and scalable tool rental system. The application serves as a point-of-sale tool for stores, similar to Home Depot, that rents out large tools. When a customer rents a tool, a Rental Agreement is generated detailing the terms of the rental.

## Features

- **Spring Boot Backend**: The application uses Spring Boot, ensuring quick setup, embedded server capabilities, and a wide range of development tools.
- **Tool Catalog Management**: Maintain a catalog of tools available for rent with unique attributes.
- **Rental Agreement Generation**: Generate detailed rental agreements upon tool checkout.
- **Flexible Pricing Model**: Set different daily rental charges, with special pricing for weekends or holidays.
- **Discount System**: Apply discounts to the total daily charges, offering flexibility in pricing for customers.

## Tool Catalog

| Tool Code | Tool Type   | Brand   | Daily Charge | Weekday Charge | Weekend Charge | Holiday Charge |
|-----------|-------------|---------|--------------|----------------|----------------|----------------|
| CHNS      | Chainsaw    | Stihl   | $1.49       | Yes            | No             | Yes            |
| LADW      | Ladder      | Werner  | $1.99       | Yes            | Yes            | No             |
| JAKD      | Jackhammer  | DeWalt  | $2.99       | Yes            | No             | No             |
| JAKR      | Jackhammer  | Ridgid  | $2.99       | Yes            | No             | No             |

## Technical Stack

- **Framework**: Spring Boot
- **Database**: (Specify the database used, e.g., H2, MySQL, PostgreSQL)
- **ORM**: Spring Data JPA (if used)
- **API Documentation**: Swagger (if used)
- **Testing**: JUnit with Spring Boot Test

## Setup & Running the Application

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ericpalmer327/ep0823.git
2. **Build the Application**:
   ```bash
   mvn clean install
3. **There is Swagger documentation so APIs can be tested on Swagger**:

