# Project Overview
This project is a web application designed to manage salary data and internship applications. It provides insights and tools for both interns and employers.

# Features
- User authentication and authorization
- Salary management system
- Application tracking for interns
- Responsive design for multiple devices

# Installation
1. Clone the repository:  
   `git clone https://github.com/daotrang0208-a11y/salarry-intern-web.git`
2. Navigate to the project directory:  
   `cd salarry-intern-web`
3. Install the dependencies:  
   `npm install`

# Setup
1. Create a `.env` file in the root directory and add your environment variables:
   - `DATABASE_URL`=
   - `API_KEY`=
2. Start the development server:  
   `npm start`

# Usage
1. Visit `http://localhost:3000` in your web browser.
2. Register as a new user to access the application.
3. Follow the instructions to manage salaries and intern applications.

# API Integration
- The application integrates with the following APIs:
  - User authentication API
  - Salary calculation API
  - Internship opportunity API

# Project Structure
```
/ ------ Root directory
|-- /src ------ Source files
|   |-- /components ------ React components
|   |-- /pages ------ Application pages
|   |-- /utils ------ Utility functions
|-- package.json ------ Project metadata and dependencies
|-- .env ------ Environment variable definitions
```

# Troubleshooting
1. **Problem: Unable to connect to database**  
   Solution: Check your `DATABASE_URL` in the `.env` file. Ensure the database server is running.

2. **Problem: API requests failing**  
   Solution: Verify your `API_KEY` in the `.env` file and ensure the API service is reachable.

3. **Problem: Application not starting**  
   Solution: Ensure all dependencies are installed and there are no errors in the console.