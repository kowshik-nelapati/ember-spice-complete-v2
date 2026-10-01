# Ember Spice Restaurant

[🌐 View Live Website](https://ember-spice-restaurant.onrender.com)
# Ember & Spice — Full-Stack Restaurant Portfolio Website

A premium restaurant website built as a portfolio/demo project for a web agency.

## Stack
- Frontend: HTML5, CSS3, vanilla JavaScript
- Backend: Node.js + Express
- Data: JSON files (simple and deployment-friendly for a demo)
- Admin: JWT authentication

## Run locally
1. Install Node.js 18+.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.
6. Admin dashboard: `http://localhost:3000/admin.html`

### Demo admin login
Email: `admin@emberandspice.com`
Password: `admin123`

For production, change the credentials and JWT secret through environment variables and use a real database.

## API
- `GET /api/menu`
- `POST /api/reservations`
- `POST /api/contact`
- `POST /api/admin/login`
- `GET /api/admin/dashboard` (auth)
- `PATCH /api/admin/reservations/:id` (auth)
- `PATCH /api/admin/messages/:id` (auth)
- `POST /api/admin/menu` (auth)
- `DELETE /api/admin/menu/:id` (auth)

## Agency portfolio positioning
Use this as a demo project under your agency portfolio. Replace the restaurant name, address, images, menu and branding with a client's real details before delivery.


### Restaurant contact / notifications
The restaurant booking and order contact is configured as **+91 86391 83884**. Customer submissions return a WhatsApp notification link for that number. For automatic outbound WhatsApp/SMS messages, connect a provider such as Twilio/WhatsApp Cloud API and add its credentials to `.env`; the website itself cannot send SMS/WhatsApp without such a provider.
