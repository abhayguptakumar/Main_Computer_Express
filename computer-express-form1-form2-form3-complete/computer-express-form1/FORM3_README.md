# Form 3 — Admin Panel & Backend Preparation

Form 3 adds the admin-side frontend for Computer Express and shares the same browser storage used by Form 1 and Form 2.

## Admin demo login
- Email: `admin@computerexpress.local`
- Password: `Admin@123`

Open: `form3/admin-login.html`

## Modules
1. Products — add/edit/delete products, price and stock
2. Categories — manage categories
3. Inventory — stock and low-stock alerts
4. Orders — view Form 1 orders and update status
5. Customers — view Form 2 registered users and activity
6. Bookings — view Form 2 service bookings and update status
7. Offers/Banners — create promotional entries
8. Reports — order, booking and stock summaries
9. Settings — store/support settings for the prototype

## Shared storage keys
- `computerExpressProducts`
- `computerExpressUsers`
- `computerExpressOrders`
- `computerExpressBookings`
- `computerExpressAdmin`
- `computerExpressCategories`
- `computerExpressOffers`
- `computerExpressSettings`

## Important
This is still a frontend/localStorage prototype. Do not use the demo admin credentials or localStorage authentication in production. The next backend phase should move authentication, authorization, products, inventory, orders, customers, bookings, payments and reports to a server/database.

## Merge architecture
Keep one repository and one root project. Form 1 stays in `/`, Form 2 stays in `/form2/`, and Form 3 stays in `/form3/`. Shared product data is read through `/js/products.js`; Form 3 writes product overrides to localStorage so public Form 1 pages can immediately see admin product changes in the same browser.
