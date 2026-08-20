# Euroclean Cleaning Service — website

High-end marketing site with a self-serve instant-quote and booking flow for
Euroclean Cleaning Service, Jacksonville FL.

- Single static `index.html`. No build step, no dependencies.
- `og.png` is the 1200x630 link-preview card.
- The quote engine, calendar and validation are all client side.

## Not yet wired
Booking confirmation is client side only. The confirm screen hands the customer
a prefilled SMS and email to the office; there is no server writing the booking
to a database. Wiring it to Supabase + a transactional email is the next wave.
