---

# Carpooling Web Application

## Description

This project is a carpooling web application designed to facilitate easy and efficient ride-sharing for users. Built with the MERN stack, it leverages MongoDB for database management, Express.js and Node.js for the backend, and React for the frontend. The application aims to reduce travel costs, decrease traffic congestion, and minimize environmental impact by connecting drivers with empty seats to passengers looking for a ride.

## Features

- **User Authentication**: Secure signup/login functionality for drivers and passengers.
- **Profile Management**: Users can create and edit their profiles, including vehicle details for drivers.
- **Ride Matching**: Algorithm to match passengers with drivers based on destination, time, and preferences.
- **Ratings and Reviews**: Users can rate and review each other to ensure safety and trustworthiness.
- **Responsive Design**: Fully responsive web design for a seamless experience on any device.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/PasanAbeysekara/carpool-full-stack-mern
   cd carpool-full-stack-mern
   ```

2. **Install Dependencies**

   - For the server:

     ```bash
     cd backend
     npm install
     ```

   - For the client:

     ```bash
     cd frontend
     npm install
     ```

3. **Set up Environment Variables**

   - Create a `.env` file in the backend directory and add your MongoDB URI and other config variables like:

     ```plaintext
     MONGO_URI=your_mongodb_uri
     PORT=5000
     ```

4. **Run the Application**

   - Start the backend server:

     ```bash
     npm start
     ```

   - In a new terminal, start the React frontend:

     ```bash
     cd frontend
     npm start
     ```

   Your app should now be running on `http://localhost:3000`.

## Usage

After installation, users can register as a driver or passenger, complete their profiles, and start offering or booking rides. The application's intuitive interface makes it easy to navigate through available rides, communicate with other users, and manage bookings.

## License

This project is licensed under the [MIT License](LICENSE).

---
