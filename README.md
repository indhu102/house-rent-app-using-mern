HouseHunt – Finding Your Perfect Rental Home 📌 Project Overview

HouseHunt is a full-stack rental web platform that bridges the gap between property owners and renters. It simplifies the rental process by enabling seamless property listings, search with filters, booking requests, owner approval, and admin moderation—offering a smooth and transparent rental experience for all users.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript, React, Bootstrap, Axios Backend: Node.js, Express.js Database: MongoDB Other Modules: JWT Authentication, Cloudinary (for image uploads) Deployment: Netlify (Frontend), Render (Backend), MongoDB Atlas

🔧 Features

User Roles: Renter / Owner / Admin

Authentication: Secure user registration and login using JWT

Property Listings: Owners can post rental properties with images, descriptions, and pricing

Search & Filters: Renters can search by location, budget, number of rooms, and amenities

Booking Requests: Renters can send booking requests to property owners

Owner Approval: Owners can approve or reject booking requests

Admin Dashboard: Manage users, properties, and monitor reports

Notifications: Email or in-app alerts for booking status and updates

Responsive UI: Mobile and desktop-friendly design

🧩 Solution Architecture

HouseHunt follows a robust client-server architecture using RESTful APIs and MongoDB for data persistence. Key modules include:

Frontend UI: Built with React, handles user interaction and dynamic rendering

Backend API: Node.js & Express.js handle business logic, routes, and authentication

Database: MongoDB Atlas stores user data, listings, and booking details

Admin Panel: Securely manages users, listings, and reports

Media Uploads: Cloudinary integration for storing property images

Authentication: JWT tokens protect user sessions and API routes
