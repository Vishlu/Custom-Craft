# CustomCraft - E-commerce Platform for Custom Electronics

![CustomCraft](https://img.shields.io/badge/Live-Demo-brightgreen)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-brightgreen)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)

A full-stack e-commerce platform that enables users to customize electronic devices and compare vendor pricing with seamless order management and secure payment processing.

## 🚀 Live Demo

**[https://customcraft.onrender.com/index.html](https://customcraft.onrender.com/index.html)**

## 📋 Project Overview

**CustomCraft** is an innovative e-commerce solution built to revolutionize the custom electronics market. The platform allows users to:
- Configure and customize electronic devices according to their preferences
- Compare pricing from multiple vendors
- Streamline the purchasing process with secure payment integration
- Manage orders through an intuitive workflow system

## 🗓️ Project Timeline
**Mumbai, India** | **May 2025 – September 2025**

## ✨ Key Features

- **Device Customization**: Interactive interface for configuring electronic devices
- **Vendor Comparison**: Real-time price comparison across multiple vendors
- **Shopping Cart**: Add-to-cart functionality with persistent storage
- **Order Workflow**: Complete order management from customization to confirmation
- **Secure Payments**: Integrated payment gateway for safe transactions
- **User Authentication**: Secure login and registration system
- **Responsive Design**: Optimized for both desktop and mobile devices

## 🛠️ Tech Stack

### Frontend
- **React JS** - Modern UI framework for building interactive user interfaces
- **HTML5/CSS3** - Structure and styling with responsive design
- **JavaScript ES6+** - Client-side functionality and API integration

### Backend
- **Node JS** - Runtime environment for server-side operations
- **Express JS** - Web application framework for building RESTful APIs

### Database
- **MongoDB** - NoSQL database for flexible data storage and retrieval

### Deployment
- **Render** - Cloud platform for deployment and hosting

## 🔧 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account or local MongoDB instance
- npm or yarn package manager

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/customcraft.git
   cd customcraft

# Install server dependencies
cd backend
npm install

# Install client dependencies
cd ../frontend
npm install


MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
npm start

customcraft/
├── frontend/                 # React application
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── context/        # React context for state management
│   │   └── utils/          # Utility functions
│   └── public/             # Static assets
├── backend/                 # Node.js server
│   ├── models/             # MongoDB models
│   ├── routes/             # API routes
│   ├── middleware/         # Custom middleware
│   └── controllers/        # Route controllers
└── README.md
