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
1. Go to the backend folder and create 2 files: **.env** and **.env.e2e**, then add this content in both of them:

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

2. **MongoDB Setup:**
  - Create an account in mongoDB Atlas
  - Create a new cluster for the database
  - Get the MongoDB connection and add it to **MONGODB_CONNECTION_STRING** in the .**env** files.

3. **Cloudinary Setup:**
  - Create an account at Cloudinary
  - In your dashboard find your cloud name, API key, API secret.
  - Add the variables in your **Cloudinary Variables** in your **.env** files.

4. **Stripe Setup:**
  - Create an account at Stripe
  - In your dashboard find your API key.
  - Add your API key in yout **Stripe** in your **.env** file.

5. **JWT_SECRET_KEY:**
  - Add a random key.

6.**Frontend URL:**
  - Your **FRONTEND_URL** points to the location of your backend (usually **http://localhost:7000**).

## Start the application
1. Backend:
  - Go to the **backend** folder
  - At the end of the **backend** folder type: **npm install**
  - Start the server with: **npm start**
    
2. Frontend:
  - Go to the **frontend** folder
  - At the end of the **frontend** folder type: **npm install**
  - Start the application with: **npm run dev**
  - Go to the browser and search: **http://localhost:5173**



