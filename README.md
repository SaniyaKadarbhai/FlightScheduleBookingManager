# FlightScheduleBookingManager-CPP

## A Console-Based Flight Schedule and Booking Management System in C++

This project implements a command-line application in C++ designed to manage flight schedules and handle passenger bookings. It provides a simple interface for adding new flights and for customers to book seats on available flights. The system demonstrates object-oriented programming principles through the use of classes for Flight, Passenger, Ticket, and Booking.

## ✨ Features

* **Flight Management:** Add new flights with details like flight number, origin, destination, departure/arrival times, total seats, and fare.

* **Booking System:** Allows users to select an available flight and book multiple passengers.

* **Real-time Seat Availability:** Tracks and updates the number of available seats on a flight after each booking.

* **Passenger Details:** Records passenger names and passport numbers for each booking.

* **Ticket Generation:** Automatically generates a ticket for each booked passenger, including flight details, seat number (simplified), and fare.

* **Booking Summary:** Displays a comprehensive summary of each booking, including flight information, passenger list, generated tickets, and total fare.

* **User-Friendly Interface:** Simple menu-driven navigation for ease of use in the console.

## 🚀 Technologies Used

* **C++ Language:** The core programming language.

* **Object-Oriented Programming (OOP):** Utilizes classes (`Flight`, `Passenger`, `Ticket`, `Booking`) to encapsulate data and behavior, promoting modular and maintainable code.

* **Standard C++ Libraries:**

  * `iostream`: For console input and output.

  * `vector`: For dynamic arrays, used to store multiple flights and passengers/tickets within a booking.

  * `string`: For handling text data such as flight numbers, names, and locations.

  * `limits`: Used with `cin.ignore` for robust input handling.
