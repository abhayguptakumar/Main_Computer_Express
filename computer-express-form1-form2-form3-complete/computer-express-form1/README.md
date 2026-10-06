# Computer Express — Form 1

Form 1 is the **frontend public shopping flow only**.

## Run
Open `index.html` in a browser, or use VS Code Live Server.

## Flow
Home → Products → Product Details → Cart → Checkout → Payment Demo → Order Confirmation

## Included
- Responsive glassmorphism UI
- Dark navy/cyan Computer Express branding
- Product categories
- Product search/filter
- Product details
- Cart using localStorage
- Checkout UI
- Demo payment
- Demo order confirmation
- About / Contact / FAQ / Terms / Privacy / Refund placeholders
- Login UI placeholder for Form 2

## Important
No real backend, database, authentication or payment gateway is connected yet.

When Form 2 and Form 3 are added later:
- Keep the same header/footer.
- Replace localStorage cart with API/database cart.
- Connect login/register to authentication.
- Connect service booking to backend.
- Connect admin product/order/inventory management to the same database.
- Replace demo payment with a real payment gateway after backend/security setup.


## Device Responsive Requirement
Form 1 is designed to be responsive across:
- Mobile phones
- Tablets
- Laptops
- Desktop monitors
- Large 4K displays
- Smart TVs / very large screens

The CSS uses viewport meta settings, fluid widths, responsive grids, touch-friendly controls, and large-screen breakpoints. The layout adapts rather than simply stretching the mobile version.

## Form 2 Added
Form 2 is now included in `form2/` and adds service booking + user account flows. The Form 1 header now points Services to `form2/services.html` and Login to `form2/login.html`.

## Form 3 — Admin Panel

Open `form3/admin-login.html` for the admin frontend.

Demo credentials: `admin@computerexpress.local` / `Admin@123`

### One-project merge structure
- Form 1: root pages (`index.html`, `pages/`, `css/`, `js/`)
- Form 2: `form2/`
- Form 3: `form3/`

Do not create three separate repositories. Use one GitHub repository for the complete Computer Express project.
