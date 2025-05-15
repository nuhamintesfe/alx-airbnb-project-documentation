# Airbnb Clone Backend Requirements

## 1. User Auth
- POST /register
- POST /login
- Use JWT
- Role: guest, host, admin

## 2. Listings
- POST /properties
- PUT /properties/:id
- DELETE /properties/:id

## 3. Bookings
- POST /bookings
- GET /bookings
- Cancel / Update booking

## 4. Payments
- POST /payments
- Supports Stripe
- Currency conversion

## 5. Reviews
- POST /reviews
- Only after booking
