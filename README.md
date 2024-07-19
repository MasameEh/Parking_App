# Parking
It's a parking app built using Flutter for the frontend and FastAPI with a SQL database for the backend.

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

## Screenshots

<img src="https://github.com/user-attachments/assets/5e372012-681d-435e-93e0-a83078fc2342" alt="SIGNUP" width="200" />

<img src="https://github.com/user-attachments/assets/1033a276-5dd5-4475-afb3-0e6c1582bdf2" alt="signin" width="200" />

<img src="https://github.com/user-attachments/assets/bd678eb5-6ff8-4d33-b39b-5d5ccbe0d6ee" alt="profile" width="200" />

<img src="https://github.com/user-attachments/assets/b969ca05-31ae-4b7a-b957-abbf7afb5562" alt="lots" width="200" />

<img src="https://github.com/user-attachments/assets/39e5b978-ac01-46ab-8b8f-3aee7b412027" alt="desc" width="200" />

<img src="https://github.com/user-attachments/assets/814622f7-c129-4ca3-b345-62407a602209" alt="v" width="200" />

<img src="https://github.com/user-attachments/assets/b9ca7839-1042-4b1f-9f2d-8911504f5da9" alt="All" width="200" />

<img src="https://github.com/user-attachments/assets/1a7fc35d-b9d9-4fdd-a583-8009a9b8998d" alt="ticket" width="200" />

<img src="https://github.com/user-attachments/assets/e673468c-0312-49d2-8de7-77c58e2c7449" alt="timer" width="200" />

# Backend
https://github.com/Muhammad-Abdelsattar/parking-lots-management-system
