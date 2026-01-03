MD Parfums - Installation & Execution Guide
This project is a full-stack e-commerce application developed using React, Spring Boot, and MySQL. Follow the steps below to set up and run the project on your local environment.

1. Database Configuration
Navigate to the /SourceCode/database directory.

Import the provided .sql file into your MySQL server using a tool like MySQL Workbench.

The database contains the necessary tables for perfumes, users, and order history.

2. Backend Setup (Spring Boot)
Open the /SourceCode/backend folder using IntelliJ IDEA.

Ensure Maven is used for dependency management.

Run the application. The backend service will start at http://localhost:8080.

3. Frontend Setup (React)
Open a terminal and navigate to the /SourceCode/frontend directory.

Install the required dependencies by running the following command:
npm install

Start the development server with:
npm start

The application will open automatically in your browser at http://localhost:3000.

📌 Project Requirements Checklist
JS Framework: React (using Context API for Auth and Cart management).

Component Library: Material UI (for responsive and professional design).

Backend: Spring Boot (REST API integration).

Home Page: Dynamically lists featured products pulled from the backend service.

Design Principles: Applied visual hierarchy, multi-step checkout logic, and mobile responsiveness.

Note: Please ensure the Backend is running first, as the Frontend fetches product data and search results from the active Spring Boot API.
