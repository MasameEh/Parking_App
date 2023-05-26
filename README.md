# BemyGuide
This repository contains the code for a parking app built using Flutter for the frontend and FastAPI with a SQL database for the backend.
A new Flutter project.

# Features
User Registration: Users can sign up for an account by providing their details such as name, email, and password.

User Login: Registered users can log in to their accounts using their email and password.

A customer can make a reservation in any of the parking lots.

Whenever a reservation is created, its state becomes pending.
The parking lot manager must activate the reservation to make it active.
A customer may not have more than one pending reservation. If a
customer wants to make another reservation while having one pending
reservation, they must first cancel the existing reservation (only possible
while the reservation is pending).

Each parking lot has an allowance time in minutes, which is the
maximum time a customer can be late before their reservation
becomes eligible for cancellation by the manager.

A parking lot manager can cancel a reservation only if it's pending and
the allowance time has passed.

# Backend
https://github.com/Muhammad-Abdelsattar/parking-lots-management-system
