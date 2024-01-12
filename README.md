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

### IMAGES WEBSITE
 (
![Screenshot 2024-01-12 172911](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/e2e15b25-83b6-4af1-aa51-823a8a2c9946)
)![Screenshot 2024-01-12 172911](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/b83d1e50-2625-4b7f-9aee-70a8bb44b761)
![Screenshot 2024-01-12 173619](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/1235fbcd-823a-4ec4-9f99-623f970a1a37)
![Screenshot 2024-01-12 173530](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/8aba793c-c480-40e0-894a-ce647fbbb513)
![Screenshot 2024-01-12 173513](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/eaceb065-a8af-4fd9-823b-f255c4a1e045)
![Screenshot 2024-01-12 173344](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/deda45c4-7ad0-4a14-8cd6-7ed952b38833)
![Screenshot 2024-01-12 173226](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/7f7b8695-9df1-45fd-82e7-d7fef521e2b2)
![Screenshot 2024-01-12 173054](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/1e0a8338-c6f0-468d-a2a9-e6aa371062dc)
![Screenshot 2024-01-12 173038](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/ed3b453e-0f61-41cd-837d-9eb494d914e1)
![Screenshot 2024-01-12 173028](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/35b96383-b2ce-4596-b01c-19593748c2fd)
![Screenshot 2024-01-12 173006](https://github.com/vikasutf8/Real-Estate-Project/assets/117626243/2f3bb5d0-1e8c-4f6f-ae79-a4e62c3edcd2)


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
