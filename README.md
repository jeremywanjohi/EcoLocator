# Ecolocator

Ecolocator is a mobile application designed to help users locate recycling centers and earn rewards for their recycling activities. The app promotes sustainable practices by incentivizing recycling and making it easy for users to find the nearest recycling centers.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Project Setup/Installation Instructions

### Dependencies:
- Node.js
- MySQL
- Expo CLI
- React Native
- Nodemailer
- bcryptjs
- cors

### Installation Steps:

#### Backend Setup:

1. **Navigate to the backend directory:**
   ```bash
   cd ecolocator-backend
   
2. **Install Dependencies:**
   ```bash
   npm install

3. **Set up the MySQL database:**
   Create a database named ecolocator.
   Use the provided SQL script to create tables.

4. **Start the backend server:**
   ```bash
   node src/index.js

#### Frontend Setup:

1. **Navigate to the frontend directory:**
   ```bash
   cd ecolocator-frontend/ecolocator-app

2. **Install Expo CLI globally if not already installed:**
   ```bash
   npm install -g expo-cli

3. **Install Dependencies:**
   ```bash
   npm install

4. **Start the Expo project:**
   ```bash
   npx expo start

### Examples:

#### Registration:
- Register a new user via the registration form on the mobile app.
- An activation email will be sent to the registered email address.

#### Login:
- Log in using the registered email and password.

#### Recycling Activities:
- Navigate to the "Find Nearest Place" to locate nearby recycling centers.
- Check the "Stores & Rewards" section to view available stores and rewards.

### Input/Output:

#### Input:
- User details for registration (email, password, phone number, first name, last name).
- Location data for finding nearby recycling centers.

#### Output:
- User rewards and available recycling stores.
- Directions to the nearest recycling center.

   








