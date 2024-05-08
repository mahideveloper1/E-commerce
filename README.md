# E-commerce App

This is a full-stack E-commerce web application built using the MERN stack. It allows users to browse products, add them to the cart, make payments, and manage their profile.

## Features

- **Authentication**: User authentication is implemented using JWT (JSON Web Tokens). Users can sign up, log in, and log out securely.
- **Product Catalog**: Browse through a wide range of products available in the store.
- **Product Search**: Users can search for products by name.
- **Product Filtering**: Products can be filtered based on different categories.
- **Product Details**: Users can view detailed information about a product.
- **Shopping Cart**: Users can add products to the cart and manage the cart.
- **Checkout and Payments**: Integrated payment system for a seamless checkout experience.
- **User Profile**: Users can view and edit their profile information.
- **Pagination**: Paginated display for better user experience.
- **Responsive Design**: The application is fully responsive and works well on all devices.

## Technologies Used

- **Frontend**:

  - React.js
  - Redux for state management
  - React Router for routing
  - Material-UI for UI components
  - Axios for making HTTP requests

- **Backend**:

  - Node.js
  - Express.js
  - MongoDB for database
  - Mongoose for object modeling
  - JSON Web Tokens (JWT) for authentication

- **Payment Gateway**:
  - Stripe

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mahideveloper1/E-commerce

   ```

2. Navigate to the project directory:

   cd ecommerce-app

3. cd ecommerce-app

cd frontend
npm install
cd ../backend
npm install

4.  Create a .env file in the backend directory and add the following environment variables:

PORT = 8080
MONGODB_URL = your mongodb url
JWT_SECRET_KEY = jwt key
SESSION_KEY = session key
MAIL_PASSWORD = nodemailer
STRIPE_SERVER_KEY = your stripe server key
ENDPOINT_SECRET = your stripe endpoint

5.  Start the backend server:

npm start

6.  Start the frontend development server:

cd ../frontend
npm start

## Contributing

Contributions are welcome! Please feel free to submit a pull request.
