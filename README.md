
## Demo Video

https://github.com/arjun-rai912/Social-Media-Web/assets/85013470/f50582af-3b8f-4583-811f-5c36a57071f0

# Social Media Web App

Welcome to the Social Media Web App GitHub repository! This is a full-stack web application built using the MERN (MongoDB, Express, React, Node.js) stack. The app allows users to connect with friends, post text and images, and toggle between light and dark modes for a personalized experience. User authentication is implemented using JWT (JSON Web Tokens), and file upload functionality is enabled using Multer.

![Social Media Web App Screenshot](screenshot.png)

## Features

- **User Authentication:** Secure user registration and login system using JWT for authentication.
- **Light and Dark Modes:** Toggle between light and dark modes to suit your preferences.
- **Friend Management:** Users can add and remove friends, enhancing their social experience.
- **Post Creation:** Create posts containing text and images to share with your friends and followers.
- **Responsive Design:** The app is designed to work seamlessly on both desktop and mobile devices.

## Technologies Used

- **Frontend:**
  - React: A JavaScript library for building user interfaces.
  - Redux: A state management library for managing global application state.
  - React Router: For handling client-side routing within the app.
  - Styled Components: CSS-in-JS library for styling components.
  - Axios: Promise-based HTTP client for making API requests.

- **Backend:**
  - Node.js: A JavaScript runtime for building server-side applications.
  - Express: A web application framework for building APIs and handling HTTP requests.
  - MongoDB: A NoSQL database for storing application data.
  - Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js.
  - JWT (JSON Web Tokens): For secure user authentication and authorization.
  - Multer: Middleware for handling file uploads.

## Getting Started

To run this application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/social-media-web-app.git
   cd social-media-web-app
   ```

2. **Install dependencies:**

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `backend` directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-secret-key
   ```

4. **Run the application:**

   ```bash
   # Start the backend server
   cd backend
   npm start

   # Start the frontend development server
   cd ../frontend
   npm start
   ```

5. Access the app by opening `http://localhost:3000` in your web browser.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to fork this repository and submit a pull request.

Please make sure to follow our code of conduct and provide detailed commit messages.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for checking out our Social Media Web App! If you have any questions or feedback, please don't hesitate to contact us.
