# SBFoods 🍲

Welcome to *SBFoods*, a convenient and user-friendly food delivery app built with the MERN stack (MongoDB, Express.js, React, Node.js). SBFoods allows users to browse a wide variety of cuisines, customize orders, and have food delivered directly to their doorstep.

## Features 🚀

- *User Authentication*: Secure login and signup functionality using JWT.
- *Browse Menu*: View diverse food options with categories, detailed descriptions, and prices.
- *Add to Cart*: Easily add or remove items from your cart.
- *Order Tracking*: Track your orders in real-time.
- *Payment Integration*: Integrated payment gateway for a smooth checkout experience.
- *Admin Dashboard*: Admins can manage menu items, view orders, and update delivery statuses.

## Tech Stack 🛠️

- *Frontend*: React.js, Redux for state management, Axios for API calls, CSS for styling
- *Backend*: Node.js, Express.js
- *Database*: MongoDB (Atlas)
- *Authentication*: JWT for user sessions
- *Payment Integration*: Stripe API (or similar)

## Getting Started 🎉

Follow these steps to set up the project locally:

### Prerequisites

- [Node.js](https://nodejs.org/) and npm installed
- [MongoDB Atlas](https://www.mongodb.com/atlas) account
- (Optional) Stripe account for payment integration

### Installation

1. *Clone the Repository*:
   bash
   git clone https://github.com/yourusername/SBFoods.git
   cd SBFoods
   

2. *Install Dependencies*:
   - For the server:
     bash
     cd server
     npm install
     
   - For the client:
     bash
     cd ../client
     npm install
     

3. *Set Up Environment Variables*:
   Create a .env file in the server directory and add your configuration:
   plaintext
   PORT=8000
   MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/sbfoods?retryWrites=true&w=majority
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   

4. *Run the App*:
   - Start the backend server:
     bash
     cd server
     npm start
     
   - Start the frontend:
     bash
     cd ../client
     npm start
     

5. *Access the Application*:
   Open your browser and go to http://localhost:3000 to view the app.

## Folder Structure 📁

- */client* - Contains all frontend React code.
- */server* - Contains all backend Express code.
- */config* - Holds configuration files for database and authentication.
- */models* - Defines MongoDB models (e.g., User, Order, Food Item).
- */controllers* - Logic for handling API routes.
- */routes* - Defines API routes.

## Future Enhancements 🌟

- *Advanced Filtering*: Filter items by diet preferences, ratings, and price range.
- *Rating & Review*: Allow users to rate and review dishes.
- *Real-Time Notifications*: Notify users about delivery status updates.
- *Multiple Payment Options*: Expand payment options (e.g., PayPal, Apple Pay).

## Contact 📬

Feel free to reach out for questions or contributions!

- *Email*: support@sbfoods.com
- *GitHub*:https://github.com/vijiDdev/sbfoods
