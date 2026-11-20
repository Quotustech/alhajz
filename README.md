# Travel Booking Platform (Extranet + Booking_Engine + Backend)

## 📝 Description

This is a full-stack travel booking platform with Property Management System that includes:

- **Extranet:** Hotel_Admin dashboard for hotels to manage bookings, pricing, and availability.
- **Booking Engine:** Frontend interface for users to search, view, and book hotels and travel packages.
- **Backend API:** Node.js + Express server for data operations, user management, and hotel partner APIs.

The platform is built using the MERN stack (MongoDB, Express, React, Node.js) and is designed for scalability and ease of use for both end-users and hotel partners.

---

## 🚀 Features

### ✈️ Booking_Engine
- Search and filter hotels and packages
- View availability and pricing
- User registration and secure login
- Make and manage bookings
- Payment gateway integration

### 🏨 Extranet
- Partner login for hotels
- Manage hotel profiles and room inventory
- Set pricing and availability calendar
- View and manage bookings

### 🖥️ Backend API
- RESTful endpoints for frontend communication
- JWT-based authentication for users and partners
- CRUD operations for hotels, rooms, bookings
- MongoDB integration for data storage

---

## 🧱 Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **Styling:** CSS Modules / Tailwind CSS / Bootstrap (customizable)

---

## 🛠️ Installation Instructions

```bash
# Clone the repository
https://github.com/Quotustech/trip-swift-extranet.git

# Backend Setup
cd trip-swift-extranet/server
setup .env file
npm install
npm run server

# Extranet Frontend Setup
cd ../extranet
setup .env file
npm install
npm start

# Booking Engine Frontend Setup
cd ../booking-engine
setup .env file
npm install
npm start


# Additional Key Features
1. Booking Engine
    Advanced hotel search with location, check-in, check-out, guest, and room filters.
    Real-time hotel availability and pricing based on selected dates.
    Dynamic room pricing based on occupancy and booking conditions.
    Room selection with detailed descriptions, images, amenities, and facilities.
    Add-on services and extra facilities during the booking process.
    Promotional offers, discount coupons, and special deals.
    Booking price calculation, including taxes, additional charges, and discounts.
    Booking history and reservation management.
    Wishlist functionality to save favorite hotels.
    User profile management and booking-related notifications.

2. Extranet (Hotel Partner Dashboard)
