# User Guide

## Registration

1. Select **Register** on the login screen.
2. Enter full name, user ID, email and password.
3. Select Student or Lecturer.
4. Confirm the password.
5. Accept the confirmation checkbox.
6. Select **Create Account**.

The account is immediately saved to the browser's localStorage.

## Login

Users can sign in with either their User ID or email address.

## Booking a laboratory

1. Open **Book a Lab**.
2. Choose a date.
3. Choose a time slot.
4. Choose a laboratory.
5. The system checks existing reservations.
6. Choose a computer or leave the computer field as Whole laboratory.
7. Select **Confirm Booking**.

The application prevents overlapping bookings for the same laboratory/computer and time slot.

## My Bookings

The page displays:

- Booking ID
- Laboratory
- Computer
- Date
- Time
- Status
- Cancellation action

## Administration

The administrator can see:

- Registered users
- User roles
- User emails
- Total bookings
- Confirmed bookings
- Demo reset control

## Data storage

The application uses JSON strings stored in `localStorage`. There is no database connection.

Clearing browser site data will remove the stored application data.
