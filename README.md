# Airbnb-clone
This Airbnb clone is a full-stack web application designed to replicate the core functionalities of Airbnb, including property listings, user authentication, booking, and review management

<img width="1440" alt="Screenshot 2024-10-29 at 13 06 00" src="https://github.com/user-attachments/assets/e44d6d13-33f7-4f64-92f7-6b32fbb69a65">


## Project Purpose
The goal of this project is to provide a comprehensive learning experience in full-stack development by implementing a real-world application. The Airbnb clone offers practice with key concepts such as:


## Backend API Development:
- Designing RESTful APIs for handling user requests, managing data, and maintaining security.
- Frontend UI Development: Building a responsive and intuitive user interface that closely resembles a real-world application.
- Database Design: Structuring a database to store complex data relationships like user profiles, bookings, and reviews.


## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Usage](#usage)

## About

This Airbnb clone project recreates the fundamental features of the Airbnb platform, focusing on user experience, responsive design, and scalability. Users can list properties, browse listings, make bookings, and leave reviews.

## Features

- **User Authentication**: Sign up, log in, and manage account settings
- **Listings**: Property owners can list their properties with details like location, price, amenities, and images
- **Search and Filters**: Users can search for properties by location, date, and other filters
- **Booking System**: Secure booking and availability management
- **Reviews and Ratings**: Users can leave reviews for properties they have stayed at
- **Responsive Design**: Optimized for mobile and desktop



## Tech Stack

### Frontend
- **HTML, CSS, JavaScript**
- **React.js**: For building user interfaces and components
- **Redux**: State management for the frontend

### Backend
- **Node.js**: Runtime environment
- **Express.js**: Backend framework
- **MongoDB**: NoSQL database for storing user, booking, and listing data
- **JWT**: JSON Web Token for secure user authentication

### Additional Tools
- **Cloudinary** (or similar): For handling image uploads
- **Mapbox API**: For interactive maps and location-based services
- **Stripe API** (or similar): For handling payments

## Setup

### Prerequisites
- Node.js and npm installed
- MongoDB set up
- (Optional) Cloudinary, Mapbox, and Stripe API keys

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kanak0983/airbnb-clone.git
   cd airbnb-clone
   ```

2. **Install dependencies:**
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Environment Variables:**  
   Create a `.env` file in the root directory and add:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_API_KEY=your_cloudinary_key
   MAPBOX_API_KEY=your_mapbox_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run the Application:**
   ```bash
   npm run dev
   ```
   The frontend will be served at `http://localhost:3000` and the backend at `http://localhost:5000`.

## Usage

- **Home Page**: View listings, search properties, and use filters
- **Login/Signup**: Create a new account or log in
- **Property Listing**: List a property as a host with details and images
- **Booking**: Make a booking on available properties
- **Reviews**: Leave a review for completed stays


