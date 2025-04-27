User Feedback System

This project is a full-stack application designed to collect, store, and display user feedback. It uses Node.js for the backend, React for the frontend, and MongoDB for storing the feedback data. This application allows users to submit feedback, which is then stored securely and displayed on a dashboard. The dashboard provides options to filter and sort the feedback.

Table of Contents

Project Overview

Technologies Used

Features

Project Structure

Setup Instructions

API Endpoints

Database Model

Additional Features

Evaluation Criteria

Project Overview

The User Feedback System allows users to submit feedback through a frontend form. The feedback is stored in a database and displayed on a dashboard, where users can view and interact with it. 
The application includes the following components:

Frontend: A form for submitting feedback and a dashboard for viewing the collected feedback.

Backend: A server to handle feedback submissions and retrievals.

Database: A database to store feedback securely.

Features

Feedback Submission: A simple form for users to submit feedback with their name, email, and feedback text.

Dashboard: A dashboard that displays submitted feedback with filtering and sorting options.

Feedback Categorization: (Optional) Users can categorize feedback into suggestions, bug reports, or feature requests.

Scalability: Backend built to handle multiple simultaneous submissions efficiently.

Responsiveness: The frontend is responsive and adjusts for different screen sizes.

Clean Code Structure: The code is modular and follows standard coding practices for maintainability.

Technologies Used

Backend: Node.js, Express.js

Frontend: React.js

Database: MongoDB (alternatively PostgreSQL)

Environment Variables: .env file for configuration

Styling: Basic CSS for styling (can be extended with frameworks like Bootstrap)

Frontend Components

App.js: Main React component that serves as the entry point for the frontend.

FeedbackForm.js: A form component for submitting user feedback.

FeedbackDashboard.js: A dashboard component that displays the submitted feedback and provides filtering and sorting options.

Backend Files

db.js: Establishes a connection to the MongoDB database.

feedbackModel.js: Defines the schema for storing feedback data.

feedbackRoutes.js: Defines the API routes for feedback submission and retrieval.

app.js: Sets up the Express server and integrates routes.

Setup Instructions

Follow these steps to run the application locally:

Prerequisites

Node.js and npm installed

MongoDB or PostgreSQL instance set up

Git for version control


Steps to Set Up

-->Clone the repository:

git clone https://github.com/yourusername/feedback-system.git

cd feedback-system

-->Install backend dependencies:

Navigate to the backend directory and install dependencies:

cd backend

npm install

-->Configure environment variables:

Create a .env file in the backend directory and add the following configuration (replace with your actual values):

DB_URI=srting

PORT=5000

-->Start the backend server:

Run the server in the backend directory:

npm start

The backend server will be running at http://localhost:5000.

-->Install frontend dependencies:

Navigate to the frontend directory and install dependencies:

cd ../frontend

npm install

-->Start the frontend development server:

Run the React app in the frontend directory:

npm start

The React app will be available at http://localhost:3000.

-->Access the application:

Open your browser and navigate to http://localhost:3000 to interact with the User Feedback System.
