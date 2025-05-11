# Flight Booking System

## Overview

The Flight Booking System is a C++ project designed to manage and facilitate the operations of an airline's flight schedules, reservations, and passenger information. This project aims to provide a user-friendly interface for managing flights, booking reservations, and handling customer inquiries.

## Features

- **Flight Management**: Add, remove flight information.
- **Reservation System**: Book, cancel, and view reservations.


-

## Technologies Used

- **Programming Language**: C++
- **Data Storage**: File handling for storing flight and reservation data
- **Development Environment**: Any C++ compiler (e.g., GCC, MSVC)

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/time960/flight-management-system.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd flight-management-system
    ```
3. **Compile the project**:
    ```sh
    g++ -I include/ -o flight_booking_system main/main.cpp src/Management.cpp src/Details.cpp src/Registration.cpp src/Ticket.cpp
    ```

## Usage

1. **Run the executable**:
    ```sh
    ./flight_booking_system
    ```
2. **Follow the on-screen prompts** to navigate through the system:
    - Login as an  passenger.
    - Manage flights.
    .


### Include Files

- **Management.h**: Header file for flight management functions.
- **Details.h**: Header file for passenger and flight details.
- **Registration.h**: Header file for user registration and login.
- **Ticket.h**: Header file for ticket booking and management.

### Source Files

- **Management.cpp**: Implementation of flight management functions.
- **Details.cpp**: Implementation of passenger and flight details functions.
- **Registration.cpp**: Implementation of user registration and login functions.
- **Ticket.cpp**: Implementation of ticket booking and management functions.

### Main File

- **main.cpp**: The main entry point of the application.

## Classes and Methods

### Management

- **addFlight()**: Adds a new flight to the system.
- **removeFlight()**: Removes an existing flight from the system.
- **updateFlight()**: Updates information about a flight.


### Details


- **getFlightDetails()**: Retrieves flight details.

### Registration

- **registerUser()**: Registers a new user.


### Ticket

- **bookTicket()**: Books a new ticket.
- **cancelTicket()**: Cancels an existing ticket.
- **viewTicket()**: Views details of a booked ticket.

## Contributing

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix:
    ```sh
    git checkout -b feature-name
    ```
3. **Commit your changes**:
    ```sh
    git commit -m "Description of changes"
    ```
4. **Push to the branch**:
    ```sh
    git push origin feature-name
    ```
5. **Create a pull request**.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

