# Airbnb Replica

Welcome to the **Airbnb Replica**! This project is a clone of the popular Airbnb platform, built to demonstrate key features such as property listings, booking functionality, user authentication, and more. It is developed using modern web technologies to showcase a scalable, full-stack web application.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication**: Users can sign up, log in, and manage their profile securely.
- **Property Listings**: Hosts can list their properties with detailed descriptions, images, and pricing information.
- **Booking System**: Users can search for available properties and make bookings.
- **Search Functionality**: Users can search for properties based on location, date, and price range.
- **Responsive Design**: Fully responsive UI that works across devices (desktop, tablet, mobile).
- **Admin Panel**: Manage users, listings, and bookings (if included).

## Technologies Used
- **Front-End**: 
  - HTML5, CSS3, JavaScript (React.js)
- **Back-End**:
  - Node.js, Express.js
- **Database**:
  - MongoDB (NoSQL Database)
- **Authentication**:
  - JWT (JSON Web Tokens)
- **Other Tools**:
  - Git for version control
  - Docker (optional for containerization)
  
## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tahahussain53110/airbnb_replica.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd airbnb_replica
   ```

3. **Install the dependencies** for both client and server:
   - For the client (React):
     ```bash
     cd client
     npm install
     ```
   - For the server (Node.js/Express):
     ```bash
     cd server
     npm install
     ```

4. **Set up the environment variables**:
   Create a `.env` file in the root of the server directory with the following variables:
   ```bash
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the application**:
   - Start the front-end client:
     ```bash
     cd client
     npm start
     ```
   - Start the back-end server:
     ```bash
     cd server
     npm start
     ```

6. **Access the application**:  
   The app will be running at `http://localhost:3000`.

## Usage
- **Sign Up/Login**: Create a new account or log in with an existing account.
- **Search Listings**: Use the search bar to find available properties.
- **Make a Booking**: Select a property, choose dates, and make a booking.
- **Host a Property**: If you are a host, you can add a new property for rent.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.

## License
This project is licensed under the **MIT License**.
