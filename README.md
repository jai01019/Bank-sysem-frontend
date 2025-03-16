Banking App Project
This is a full-stack banking application that allows customers and bankers to interact with the system. The app includes features such as user authentication (login/signup), role-based access (customer/banker), and transaction management.

1.Table of Contents
  Frontend
   Overview
   Technologies Used
   Installation and Setup
   Folder Structure
   API Integration
   Key Features

Frontend
 Overview
 The frontend is built using React.js and provides a user-friendly interface for customers and bankers to interact with the application. It includes login, signup, dashboard, and transaction management functionalities.


Technologies Used
 React.js : For building the frontend UI.
 React Router DOM : For routing between pages.
 Axios/Fetch API : For making HTTP requests to the backend.
 Environment Variables : For managing API URLs and sensitive data.


Installation and Setup
 1 Clone the Repository :
    git clone https://github.com/your-repo/banking-app.git
    cd banking-app/frontend

2 Install Dependencies
  npm install

3 Set Environment Variables
  Create a .env file in the frontend folder and add the following:
  REACT_APP_BASE_URL=http://localhost:5000

4 Run the Development Server
  npm start

Folder Structure

/frontend
  ├── public/            # Static assets
  ├── src/
  │   ├── components/    # Reusable components (e.g., Login, SignUp)
  │   ├── App.js         # Main application component
  │   ├── index.js       # Entry point
  │   └── styles/        # Global styles (optional)
  ├── .env               # Environment variables
  ├── package.json       # Dependencies and scripts
  └── README.md          # Frontend documentation

API Integration

 The frontend interacts with the backend via REST APIs. Below are the key endpoints used:
    ![image](https://github.com/user-attachments/assets/38e91af8-c482-4b7e-b119-93bea22bed83)

Key Features
 1 Role-Based Access :
    Customers can view their balance and transaction history.
    Bankers can manage customer accounts.
2 Authentication :
    Secure login and signup using JWT tokens.
3 Responsive Design :
    Styled for optimal viewing on desktop and mobile devices.
4 Error Handling :
    Displays appropriate error messages for invalid inputs or API failures

     
 
