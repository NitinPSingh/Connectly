
# Connectly - Social Media App

Connectly is a full-stack social media application built using the MERN stack (MongoDB, Express, React, Node.js) with JWT authentication and Redux Toolkit for state management.

## Features

- **User Authentication**: Secure user registration and login with JWT authentication.
- **Create Posts**: Users can create, edit, and delete posts.
- **Like and Comment**: Users can like and comment on posts.
- **User Profiles**: View and edit user profiles with avatar images.
- **Follow and Unfollow**: Users can follow and unfollow other users.
- **Feed**: See a feed of posts from followed users.
- **Notifications**: Receive real-time notifications for likes and comments.
- **Search Users**: Find and connect with other users.
- **Responsive Design**: The app is optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**:
  - React
  - Redux Toolkit for state management
  - Axios for HTTP requests
  - Material-UI for UI components

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB and Mongoose for database
  - JWT for authentication
  

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/connectly.git
   cd connectly
   ```

2. **Install Dependencies**:

   ```bash
   # Install server dependencies
   cd server && npm install

   # Install client dependencies
   cd ../client && npm install
   ```

3. **Set Environment Variables**:

   Create a `.env` file in the `server` directory with the following variables:

   ```
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the Development Server**:

   In separate terminals, run:

   ```bash
   # Start server
   cd server && npm start

   # Start client
   cd client && npm start
   ```

5. **Open in Browser**:

   Open your browser and go to `http://localhost:3000` to view the app.

## Contributing

We welcome contributions! Please fork this repository and create a pull request with your changes. Make sure to follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

---


Remember to provide clear instructions for contributors and adhere to licensing terms.
