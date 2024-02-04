# MERN BOOKING APP
- Ability to authenticate users, using HTTP cookies and JWT for a better experience.
- Hotel management, add, edit, and view hotels.
- Image upload, integration to upload and manage images. (Cloudinary)
- Search filters, ability to filter, list and search for hotels as required by the user.
- Online payments, integrating stripe for payment management.
- Reservation management, to view and manage reservations.
- Recent hotels on the homepage, to keep the content dynamic.

## Clone repository

## Backend configuration
- Go to the backend folder and create 2 files: .env and .env.e2e, then add this content in both of them:
  ```
MONGODB_CONNECTION_STRING=

JWT_SECRET_KEY=
FRONTEND_URL=

# Cloudinary Variables
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Stripe
STRIPE_API_KEY=
  ```
