# Backend for LiveCourierTrackingIP

This directory contains the backend for the LiveCourierTrackingIP project. It's developed with Node.js, Express, and features:

- RESTful API for shipment tracking
- JWT-based authentication for admin users
- Real-time updates using Socket.io

### Installation
#### 1. Navigate to `backend` directory:
```bash
cd backend
```
#### 2. Install Dependencies:
```bash
npm install
```
#### 3. Run the Server Locally:
```bash
npm run start-dev
```

### Folder Structure
```plaintext
/backend
│  server.js
├─ /routes
│    authRoutes.js, trackingRoutes.js
├─ /controllers
│    authController.js, shipmentController.js
├─ /models
│    Admin.js, Shipment.js
├─ /middleware
│    authMiddleware.js
```