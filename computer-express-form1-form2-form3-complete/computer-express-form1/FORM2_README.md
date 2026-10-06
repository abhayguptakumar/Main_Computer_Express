# Computer Express — Form 2

Form 2 extends the Form 1 static frontend with the **Services Booking + User Account** flow from the workflow diagram.

## Included
- Services page
- Service booking page
- Booking confirmation with Booking ID
- Login / Register
- User dashboard
- My Orders
- My Bookings
- Profile Settings
- LocalStorage-based demo data so the complete flow works without a backend
- Form 1 navigation connected to Form 2 Services and Account pages
- Form 1 demo orders are linked to the logged-in user when an order is placed

## Important
This is still a frontend prototype. Passwords and bookings are stored in browser localStorage. Do **not** use this authentication approach in production. In Form 3, replace these functions with real API/database authentication, sessions/JWT, server-side validation, payment gateway callbacks, and admin-controlled booking/order status.

## How to run
Open `index.html` with VS Code Live Server. Then:
1. Open **Services** from the header.
2. Register an account.
3. Book a service.
4. Check Dashboard → My Bookings.
5. Shop from Form 1, place the demo order while logged in, then check Dashboard → My Orders.
