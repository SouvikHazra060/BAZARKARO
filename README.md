# BAZARKARO - E-commerce Clothing Web App

BAZARKARO is a full-featured e-commerce platform for buying and selling clothes online. This project is built using the MERN stack and Bootstrap for styling, offering a responsive and user-friendly interface for both customers and admins.

## Features

- **User Authentication**: Secure login and registration system with JWT authentication.
- **Product Catalog**: Browse, search, and filter clothing items.
- **Shopping Cart**: Add/remove items from the cart, update quantities, and proceed to checkout.
- **Order Management**: Track orders, view order history, and manage payments.
- **Admin Dashboard**: Manage products, categories, orders, and users.
- **Responsive Design**: Built with Bootstrap for a mobile-first, responsive UI.

## Technologies Used

- **Frontend**:
  - React.js
  - Bootstrap
  - Axios for API calls
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB with Mongoose for database
  - JWT for authentication
- **Other Tools**:
  - Redux for state management
  - Cloudinary for image uploads
  - PayPal/Stripe API for payment processing
  - Git for version control

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB (local or cloud)
- Cloudinary account (for image hosting)
- PayPal/Stripe account for payment gateway

### Folder Structure 
bazarkaro/
├── client/                  # React frontend code
│   ├── public/              # Public assets
│   └── src/                 # React components, hooks, and pages
├── server/                  # Express backend code
│   ├── controllers/         # API controllers
│   ├── models/              # Mongoose models
│   ├── routes/              # API routes
│   └── middleware/          # Authentication, error handling, etc.
└── .env                     # Environment variables
