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
    Centralized hotel management dashboard.
    Manage multiple properties, room types, and room configurations.
    Update room rates and availability through a calendar-based interface.
    Manage inventory and room allocation.
    Configure hotel policies, cancellation rules, and booking restrictions.
    Manage seasonal pricing and special promotional rates.
    View, confirm, modify, and cancel guest reservations.
    Monitor booking statistics and property performance.
    Manage hotel amenities, room facilities, and property images.

3. Backend API
    Modular REST API architecture using Node.js and Express.js.
    Secure authentication and authorization using JWT.
    Password hashing and validation using bcrypt.
    Role-based access control for customers, hotel partners, and administrators.
    Centralized error handling and request validation.
    Database operations using MongoDB.
    Integration with third-party hotel and travel APIs.
    Booking lifecycle and reservation management.
    Dynamic pricing and availability calculation.
    API response handling and data validation.

#Advanced Functionalities

🔥 Advanced Platform Capabilities
    Dynamic Pricing: Automatically calculate room prices based on occupancy, dates, and applicable pricing rules.
    Inventory Management: Maintain room availability and prevent overbooking.
    Promotional Management: Support different promotional campaigns, discount rules, and coupon codes.
    Multi-Property Management: Allow hotel partners to manage multiple properties from a single dashboard.
    Third-Party API Integration: Connect with external hotel suppliers and channel partners.
    Booking Management: Handle the complete reservation lifecycle, from booking creation to confirmation and cancellation.
    Responsive Design: Provide a consistent user experience across desktop, tablet, and mobile devices.
    Data Synchronization: Synchronize hotel information, room availability, and pricing between integrated systems.

#Technologies Used

    Category            Technologies
    Frontend            React.js, Next.js, TypeScript
    State Management    Redux Toolkit
    Backend            	Node.js, Express.js
    Database	        MongoDB, PostgreSQL
    ORM	                Prisma
    Caching	            Redis
    Authentication	    JWT, bcrypt
    Real-time Communication	Socket.IO
    API Testing	        Postman
    Version Control	    Git, GitHub

#Booking Engine – Customer Experience
    Developed an interactive hotel booking interface that allows users to search and explore properties based on their travel preferences.
    Implemented advanced search functionality with location, check-in, check-out, room, adult, and child selection.
    Integrated dynamic hotel listing pages to display property details, room categories, available amenities, and pricing information.
    Implemented real-time availability checking to retrieve available rooms based on selected travel dates.
    Developed a room selection system that allows users to compare room categories, occupancy limits, and pricing.
    Integrated multiple pricing components, including base room rates, extra guest charges, taxes, and additional services.
    Implemented a promotional discount system to apply eligible offers and coupon codes during the booking process.
    Developed an add-on services module to allow customers to select additional facilities while making reservations.
    Implemented a wishlist feature that allows authenticated users to save and manage their favorite properties.
    Created user profile management functionality for updating personal information and managing account details.
    Integrated booking history functionality to help users track their previous and upcoming reservations.
    Implemented authentication-based navigation to protect booking-related features and user-specific information.
    Developed responsive user interfaces to ensure a seamless booking experience across different screen sizes.
    Integrated booking confirmation workflows to provide customers with reservation details after successful bookings.
    Implemented form validation and error handling to improve data accuracy during the booking process.

#Extranet – Hotel Management System
    Developed a centralized hotel administration dashboard for managing property-related operations.
    Implemented property registration and configuration functionality for hotel partners.
    Created modules for managing hotel information, room categories, facilities, and property descriptions.
    Developed room inventory management functionality to maintain room availability and allocation.
    Implemented calendar-based rate management for updating room prices across different dates.
    Created pricing configuration modules to manage seasonal rates, promotional prices, and occupancy-based pricing.
    Implemented booking management functionality for viewing and processing customer reservations.
    Developed reservation status management to track booking confirmations, modifications, and cancellations.
    Integrated hotel amenity management to maintain property-level and room-level facilities.
    Implemented configurable booking restrictions, including minimum length of stay and maximum length of stay.
    Developed promotional management modules for creating and managing hotel-specific offers.
    Implemented property-specific pricing rules and availability configurations.
    Created administrative interfaces for managing hotel images, descriptions, policies, and contact information.
    Developed booking reports and dashboard summaries to help hotel partners monitor reservation activity.
    Implemented role-based access to restrict administrative operations according to user permissions.

#Backend – API Development
    Designed and developed RESTful APIs to support communication between the Booking Engine, Extranet, and backend services.
