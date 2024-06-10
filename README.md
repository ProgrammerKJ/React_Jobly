# Job Application Project

## Description
This is a job application project with a React frontend and a backend server. The backend uses PostgreSQL as the database.

## Prerequisites
- Node.js (v14.x or higher)
- npm (v6.x or higher)
- PostgreSQL

## Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/job-application-project.git
    cd JoblyFrontAndBackend
    ```

2. **Install frontend dependencies**

    ```bash
    cd react-jobly-frontend
    npm install
    ```

3. **Install backend dependencies**

    ```bash
    cd ../backend
    npm install
    ```

## Database Setup

1. **Create a PostgreSQL database**

    ```sql
    CREATE DATABASE job_application_db;
    ```

2. **Configure database connection**

    Update the database configuration in `backend/config/db.js` or your environment variables as needed.

## Running the Project

1. **Start the frontend**

    ```bash
    cd frontend
    npm start
    ```

    The frontend will be available at `http://localhost:3000`.

2. **Start the backend**

    ```bash
    cd ../backend
    npm start
    ```

    The backend will be available at `http://localhost:5000`.

## Scripts

- **Frontend**
    - `npm start`: Runs the frontend in development mode.
    - `npm build`: Builds the frontend for production.

- **Backend**
    - `npm start`: Runs the backend server.
    - `npm run dev`: Runs the backend server with nodemon for development.
