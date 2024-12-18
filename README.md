

---

# Flight Booking App (MERN)

## Project Description

The Flight Booking App is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to search for flights, book tickets, and manage their bookings. Designed for both customers and administrators, the app provides a seamless and user-friendly experience, simplifying the flight booking process with intuitive features.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Features](#features)
  - [User Features](#user-features)
  - [Admin Features](#admin-features)
- [Tech Stack](#tech-stack)
- [Project Demo](#project-demo)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Structure

The project is organized into two main folders:

- **frontend/** - Contains the front-end React code for the Flight Booking App.
  - **src/assets/Images/** - Stores images used in the frontend.
  - **src/components/admin/** - Contains components for admin functionalities.
  - **src/components/common/** - Contains common components like login, dashboard, and navbar.
  - **src/components/user/** - Contains components for user-specific views.
  - **src/App.js** - Main React application file.
  
- **backend/** - Contains the back-end Node.js and Express code for the Flight Booking App.
  - **config/** - Database configuration.
  - **controllers/** - Contains controllers for admin and user operations.
  - **middlewares/** - Authentication middleware.
  - **routers/** - Contains route definitions for admin and user routes.
  - **schemas/** - Mongoose schemas for database models.
  - **uploads/** - Stores uploaded files (e.g., booking confirmations).
  - **index.js** - Main server file for the backend.

## Installation

### Prerequisites
- Ensure you have Node.js and npm installed. Recommended versions:
  - Node.js: v14 or higher
  - npm: v6 or higher

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/flight-booking-app.git
   cd flight-booking-app
   ```

2. **Install Dependencies**

   - **Server**
     ```bash
     cd backend
     npm install
     ```

   - **Client**
     ```bash
     cd frontend
     npm install
     ```

3. **Setup MongoDB**

   - Use either a local MongoDB instance or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) to set up a cloud database.
   
4. **Set Up Environment Variables** (See below).

## Environment Variables

Create a `.env` file in the `backend` folder and add the following variables:

```plaintext
MONGO_DB=mongodb://localhost:27017/flightbooking
PORT=5000
JWT_KEY=my_super_secret_key_123456
```

- `MONGO_DB`: MongoDB connection string.
- `PORT`: Server port (default: 5000).
- `JWT_KEY`: Secret key for JSON Web Token (JWT) authentication.

For ease, you may add a `.env.example` file to specify these variable placeholders.

## Usage

1. **Running the Server**

   The server will run on port 5000.

   ```bash
   cd backend
   node index.js
   ```

2. **Running the Client**

   The client will start on port 3000 by default.

   ```bash
   cd frontend
   npm start
   ```

## Features

### User Features

- **Flight Search**: Users can search for available flights based on destination, date, and other criteria.
- **Booking Management**: Users can book flights, view booking history, and cancel bookings.
- **User Authentication**: Sign up, log in, and log out functionality.

### Admin Features

- **Flight Management**: Admins can add, update, and delete flights.
- **Booking Management**: Admins can view and manage all bookings.
- **User Management**: Admins can view and manage all registered users.

## Tech Stack

- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Token (JWT)

## Project Demo

Here’s a quick demo showcasing the main features and functionality of the Flight Booking App, including user and admin capabilities.

- [**Demo Video**](https://drive.google.com/drive/folders/1rYn0OuLSrxWN3DIr_geeC964oDH-uirl?usp=sharing)

## Documentation

Detailed project report can be accessed here:

- [**project report**](https://github.com/Balaji849/NM_MERN-STACK/blob/master/Flight%20booking%20app%20report.pdf)

## Screenshots

For a visual overview, you can refer to this document containing project screenshots:

- [**Screenshots Document & execution**](https://github.com/Balaji849/NM_MERN-STACK/blob/master/SCREENSHOTS%20OF%20FLIGHT%20BOOKING%20APP%20%26%20EXECUTION.pdf)

## Contributing

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please make sure to update tests as appropriate and follow code style guidelines.


