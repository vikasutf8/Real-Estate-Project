# Real Estate Website

Welcome to `Real-Estate Project`, a real estate website where users can sign up, create listings for houses, and connect with property owners.

## Features

### User Authentication

- Users can sign up using a username, email, and password (encrypted using bcrypt.js).
- Sign-in functionality with email and password using JSON Web Tokens (JWT) for authorization.
- Google authentication for both sign-in and sign-out.

### House Listings

- Users, once logged in, can create, view, update, and delete listings for houses.
- Each listing includes details such as sale/rent/offer, price, additional features (parking, furnished, etc.), and photos uploaded to Firebase Storage.
- MongoDB schema "listing" is used to store house listing information.

### Categories

- Listings are categorized based on their nature: rent, sale, or offer.
- Users can easily filter and view listings by category.

### Contact Property Owner

- Other users can contact the house owner through the platform for further details or negotiations.

## Technologies Used

- Node.js and Express for the backend.
- MongoDB with Mongoose for data storage.
- Bcrypt.js for password encryption.
- JSON Web Tokens (JWT) for user authentication.
- Firebase Storage for image uploads.
- Google Authentication for user sign-in/sign-out.

## Getting Started

1. Clone the repository:

   ```bash
   gh repo clone vikasutf8/Real-Estate-Project
