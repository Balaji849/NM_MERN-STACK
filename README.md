
Screenshot & interaction with project :https://docs.google.com/document/d/1yBPq9Cmr1dKt284E-i6hF73N_9Ph8qlB/edit?usp=drive_link&ouid=103547621227644222568&rtpof=true&sd=true


Project Documentation:https://docs.google.com/document/d/1yWzJ63Rzl6Qn_m3tZruRPNgSzLmIwUGm/edit?usp=drive_link&ouid=103547621227644222568&rtpof=true&sd=true


# Flight Booking App (MERN)

## Project Description

The Flight Booking App is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to search for flights, book tickets, and manage their bookings. The app provides a seamless and user-friendly interface for both customers and administrators.

##Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Features](#features)
  - [User Features](#user-features)
  - [Admin Features](#admin-features)
- [Tech Stack](#tech-stack)
- [Project Demo](#project-demo)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Structure

The project is organized into two main folders:

- **frontend/** - Contains the front-end React code for the Flight Booking App.
  - **src/assets/Images** - Stores images used in the frontend.
  - **src/components/admin** - Contains components for admin functionalities.
  - **src/components/common** - Contains common components like login, dashboard, and navbar.
  - **src/components/user** - Contains components for user-specific views.

- **backend/** - Contains the back-end Node.js and Express code for the Flight Booking App.
  - **config/** - Database configuration.
  - **controllers/** - Contains controllers for admin and user operations.
  - **middlewares/** - Authentication middleware.
  - **routers/** - Contains route definitions for admin and user routes.
  - **schemas/** - Mongoose schemas for database models.
  - **uploads/** - Stores uploaded files (e.g., booking confirmations).

## Installation

1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/flight-booking-app.git
   cd flight-booking-app
   ```
2. Install Dependencies

   **Server**
   ```bash
   cd backend
   npm install
   ```

   **Client**
   ```bash
   cd frontend
   npm install
   ```

## Environment Variables

Create a `.env` file in the backend folder and add the following variables:

```plaintext
MONGO_DB=mongodb://localhost:27017/flightbooking
PORT=5000
JWT_KEY=my_super_secret_key_123456
```

- `MONGO_DB`: The MongoDB connection string.
- `PORT`: The server port (default: 5000).
- `JWT_KEY`: Secret key for JSON Web Token (JWT) authentication.

## Usage

**Running the Server**

The server will run on port 5000.

```bash
cd backend
node index.js
```

**Running the Client**

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

Here's a quick demo showcasing the main features and functionality of the Flight Booking App. This video walks through the user experience, highlighting both user and admin functionalities.

[![Watch the output video]]
[![screenshot]](https://docs.google.com/document/d/1yWzJ63Rzl6Qn_m3tZruRPNgSzLmIwUGm/edit?usp=drive_link&ouid=103547621227644222568&rtpof=true&sd=true)
---

This README.md file provides a clear structure and guides users through the installation, configuration, and usage of the application. You can further customize the sections based on any additional functionality or details specific to your project.
