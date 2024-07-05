
This project is an admin panel built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides   functionalities for user registration, login, logout, and CRUD operations on users. Additional features include password encryption, role-based access control, form validation, pagination, search, and error handling.

Installation and Setup
Frontend Setup

1. Initialize the Project:
    npx create-react-app admin-panel
    cd admin-panel

2. Install Dependencies:
    npm install axios react-router-dom redux react-redux bootstrap material-ui tailwindcss

3. Set Up Project Structure:
   src/components: For reusable components.
   src/pages: For different pages of the application.
   src/services: For API calls.
   src/store: For Redux store (if using Redux).

4. Run the Frontend:
    npm start
   
5. Backend Setup
    mkdir backend
    cd backend
    npm init -y

6. Install Dependencies:
    npm install express mongoose bcrypt jsonwebtoken cors dotenv

7. Set Up Project Structure:
    controllers: For handling requests.
    models: For database schemas.
    routes: For API routes.
    middlewares: For custom middleware functions.
    config: For configuration files.

8. Run the Backend:
    node server.js

