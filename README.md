# 🏠 Airbnb Clone – Full Stack Property Booking Platform

A full-stack Airbnb-inspired web application that enables users to discover properties, create listings, upload images, book stays, and manage reservations seamlessly.

The project is designed to demonstrate real-world full-stack development concepts including authentication, authorization, MVC architecture, database relationships, image management, and booking workflows.

---

## 🚀 Live Demo

🔗 Live Demo: https://air-bnb-qf4z.onrender.com

⚠️ **Note:** The application is hosted on a free-tier server, so the initial load may take a few seconds.

---

## 📸 Features

### 🔐 Authentication & Authorization

* User Registration
* User Login
* User Logout
* Session-Based Authentication using Passport.js
* Protected Routes
* Authorization for Listing Owners

### 🏡 Property Management

* Create New Listings
* Edit Existing Listings
* Delete Listings
* View Property Details
* Upload Property Images via Cloudinary

### 📅 Booking System

* Send Booking Requests
* Manage Reservations
* View Booking History
* Dynamic Booking Status Updates

### ⭐ Reviews & Ratings

* Add Reviews
* Delete Reviews
* Property Rating System

### 🔍 Search & Filtering

* Search Listings by City
* Filter Properties Based on Requirements
* Improved Property Discovery Experience

### ☁️ Cloud Image Storage

* Secure Image Uploads
* Cloudinary Integration
* Optimized Media Management

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* EJS
* Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* Passport.js
* Express Session

### Cloud Services

* Cloudinary

### Deployment

* Render

---

## 🧠 System Architecture

The application follows the **MVC (Model-View-Controller)** design pattern.

### Models

* User
* Listing
* Booking
* Review

### Views

* Dynamic pages rendered using EJS

### Controllers

* Business logic handling
* Request processing

### Routes

* RESTful routing structure
* Endpoint management

### Middleware

* Authentication checks
* Authorization checks
* Validation logic

### Utilities

* Centralized error handling
* Async wrapper functions

---

## 🔐 Authentication Flow

1. User registers or logs in.
2. Passport.js validates credentials.
3. Session is created after successful authentication.
4. Session cookie maintains login state.
5. Protected routes verify authentication before granting access.
6. Authorization ensures only owners can modify their listings.

---

## 📂 Project Structure

```bash
airbnb/
│
├── controllers/
├── models/
├── routes/
├── views/
│   ├── listings/
│   ├── users/
│   ├── bookings/
│   ├── includes/
│   └── layouts/
│
├── public/
│   ├── css/
│   └── js/
│
├── middleware/
├── utils/
├── cloudConfig.js
├── app.js
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone <repository-url>
cd airbnb
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file and add:

```env
ATLASDB_URL=
SECRET=

CLOUD_NAME=
CLOUD_API_KEY=
CLOUD_API_SECRET=

GOOGLE_MAPS_API_KEY=
```

### 4. Run the Application

```bash
node app.js

```

### 5. Open Browser

```text
http://localhost:8080
```

---

## 🎯 Learning Outcomes

Through this project I gained hands-on experience in:

* Full Stack Web Development
* MVC Architecture
* Authentication & Authorization
* Session Management
* MongoDB Schema Design
* Database Relationships
* RESTful Routing
* Cloudinary Image Uploads
* Error Handling
* Deployment on Render

---

## 💡 Future Enhancements

* Payment Gateway Integration
* Wishlist Functionality
* Advanced Property Filters
* Booking Notifications
* Performance Optimization
* Property Recommendations

---

## 👨‍💻 Author

**Akansha**

💼 LinkedIn: (http://www.linkedin.com/in/akansha-20m04)

💻 GitHub: https://github.com/Akansha7701

