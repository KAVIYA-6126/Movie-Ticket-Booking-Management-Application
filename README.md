# Movie Ticket Booking Management Application

## Overview

CineWave Entertainment manages movie ticket bookings across multiple theatres and locations. The Movie Ticket Booking Management application is built on the Pega Platform to streamline the booking process, improve visibility, and automate customer communication.

## Objectives

The application enables CineWave Entertainment to:

- Allow customers to request movie ticket bookings.
- Manage movie shows and seating availability.
- Capture customer confirmation before final booking.
- Process and track booking requests.
- Route booking requests based on show type.
- Calculate the total booking cost.
- Notify customers when their booking is successfully confirmed.

## Case Type

**Movie Ticket Request**

## Case Lifecycle

The Movie Ticket Request case follows these stages:

1. **Initial Stage** – Capture the customer's movie ticket booking request.
2. **Availability** – Check movie show and seating availability.
3. **Approval** – Obtain customer confirmation before proceeding with the booking.
4. **Booking Execution** – Complete the ticket booking and resolve the case.

## Data Objects

### Movie

Stores information about movies available for booking.

### Show

Stores information about movie shows, including show details, availability, and show type.

## Business Logic

### Total Cost

The application calculates the total cost of the requested movie tickets using the relevant booking information.

### Show Type Routing

Booking requests are automatically routed based on the show type:

- **Premium** → Premium ShowQueue
- **Standard** → Standard ShowQueue

## SLA

The Movie Ticket Request case uses the following service-level agreement:

- **Goal:** 1 day
- **Deadline:** 2 days

## Customer Communication

After a booking is successfully completed, the application automatically sends an email notification to the customer confirming the booking.

## Technology

- Pega Platform
- Pega App Studio
- Pega Blueprint
- Case Management
- Data Modeling
- Business Process Automation

## Expected Outcome

The application provides a streamlined end-to-end movie ticket booking process, from the initial customer request through availability checking, confirmation, booking execution, and final customer notification.

## Project Type

Individual Project

## Organization

CineWave Entertainment
