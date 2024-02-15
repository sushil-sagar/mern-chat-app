# MERN Chat App

This is a full-stack chat application built using the MERN (MongoDB, Express.js, React, Node.js) stack. The app allows users to engage in real-time chat conversations.

## Backend Dependencies

- **bcryptjs**: Used for hashing user passwords securely.
- **cookie-parser**: Parses cookies attached to the client request object.
- **dotenv**: Loads environment variables from a `.env` file into the process.
- **express**: Web framework for Node.js, used for handling HTTP requests.
- **jsonwebtoken**: Generates and verifies JSON Web Tokens (JWT) for user authentication.
- **mongoose**: MongoDB object modeling tool designed to work in an asynchronous environment.
- **socket.io**: Library for real-time web applications, used for enabling real-time chat functionality.

## Frontend Dependencies

- **chat-app**: Custom dependency (assumed to be a local package or component).
- **react**: JavaScript library for building user interfaces.
- **react-dom**: Provides DOM-specific methods that can be used at the top level of your app.
- **react-hot-toast**: Library for adding toast notifications to React applications.
- **react-icons**: Library for including popular icons in React projects.
- **react-router-dom**: DOM bindings for React Router, used for declarative routing in web applications.
- **socket.io-client**: Client-side library for Socket.IO, used for real-time communication with the server.
- **zustand**: Small, fast, and scaleable global state management for React.

## Dev Dependencies

- **@types/react**: Type definitions for React.
- **@types/react-dom**: Type definitions for ReactDOM.
- **@vitejs/plugin-react**: Vite plugin for React support.
- **autoprefixer**: PostCSS plugin to parse CSS and add vendor prefixes to CSS rules.
- **daisyui**: Tailwind CSS component library.
- **eslint**: JavaScript linting tool.
- **eslint-plugin-react**: ESLint plugin for React-specific linting rules.
- **eslint-plugin-react-hooks**: ESLint plugin for React Hooks-specific linting rules.
- **eslint-plugin-react-refresh**: ESLint plugin for React Refresh-specific linting rules.
- **postcss**: A tool for transforming CSS with JavaScript plugins.
- **tailwindcss**: A utility-first CSS framework for rapid UI development.
- **vite**: Next-generation frontend tooling for React projects.

## Setup .env file
PORT=3000
MONGO_DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development

## Build the app

npm run build


## Start the app

npm start

This MERN Chat App uses these dependencies to provide a secure, real-time chat experience for users while maintaining code quality and scalability.
