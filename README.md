# crypto-tracker
Crypto Tracker is a web application that allows users to track cryptocurrency prices in real-time. It features login and signup functionality and integrates with a database for storing user credentials.
Features
1.User authentication (login and signup).
2.Real-time cryptocurrency price tracking.
3.Database integration for storing user information.
4.User-friendly interface.


Technologies Used
Frontend: React, CSS
Backend: Node.js, Express
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
Crypto API: [Insert the API you used for tracking prices]


Installation
Prerequisites
Make sure you have the following installed on your system:

Node.js
npm
MongoDB (if using locally)


Steps to Run Locally

Clone the repository:
bash
git clone https://github.com/your-username/crypto-tracker.git

Navigate to the project directory:
bash
cd crypto-tracker

Install dependencies:
bash
npm install

Create a .env file in the root directory and add your environment variables, for example:
bash
MONGODB_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
CRYPTO_API_KEY=your-api-key

Run the application:
bash
npm start
Visit http://localhost:3000 in your browser to view the application.


Usage
Users can create an account by signing up, or log in with existing credentials.
After logging in, users will be able to track live cryptocurrency prices.
Data will be fetched from the crypto API and displayed in real-time.


Contributing
If you'd like to contribute to this project:

Fork the repository.
Create a new branch.
Make your changes.
Open a pull request.


License
This project is licensed under the MIT License - see the LICENSE file for details.
