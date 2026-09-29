# UniLab Computer Laboratory Booking System

## Role-based localStorage version

### Students and lecturers
- Have their own dashboard and navigation.
- Can book an **individual computer only**.
- Cannot reserve an entire laboratory.
- Can only select computers whose status is **READY FOR USE**.
- Can view and cancel their own bookings.
- Can view laboratories and their PC readiness.
- Can update their profile.

### Administrator
- Has a separate Admin Dashboard.
- Has **PC Management** for every computer.
- Can change a PC from **READY FOR USE** to **UNDER MAINTENANCE**.
- Can return a PC to **READY FOR USE**.
- Can record a maintenance reason.
- Has User Management and All Bookings pages.
- Can cancel system bookings.

### Demo accounts
- Student: `student01` / `student123`
- Lecturer: `lecturer01` / `lecturer123`
- Admin: `admin` / `admin123`

The system uses browser localStorage. No database, JDBC, PHP or backend connection is required.
