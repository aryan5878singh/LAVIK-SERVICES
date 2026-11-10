# Lavik Services — Solar E-commerce Frontend

Responsive React + Vite frontend starter for Lavik Services.

## Included
- Responsive homepage, about, product catalogue, services, office locations and contact sections
- Product category filters and client-side cart
- WhatsApp quotation links using the supplied business phone number
- Contact form that opens the visitor's email application (mailto)
- Login/register entry point placeholder for the backend integration phase

## Run locally
1. Install Node.js (LTS).
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite (normally http://localhost:5173).

## Important implementation notes
- Product names, prices, ratings and descriptions are demo placeholders. Confirm actual catalogue details before publishing.
- The account modal is a placeholder; authentication, database persistence, order management and admin functions are not connected yet.
- The contact form currently uses `mailto:`. A backend enquiry API will replace this in the integration phase.
- Checkout currently sends the selected cart items to WhatsApp. No payment gateway is connected.
