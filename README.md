# activity-2

What does your project do?
    a web API (Application Programming Interface) that manages student and course information. Think of it like a digital filing system where you can:

        - Add new students and courses
        - iew existing records
        - Update information when needed
        - Delete records when necessary

Why did you create it?

    - I created this API to provide a structured and organized way to manage educational data. This system helps schools or training programs keep track of their students and courses efficiently. It demonstrates practical CRUD (Create, Read, Update, Delete) operations which are fundamental to most web applications.

How can someone run your code?

        - Install dependencies: Run npm install to install all required packages
        - Set up database: Create a MySQL database and configure the connection in the .env file
        - Start the server: Run npm run dev for development or npm start for production
        - Access endpoints: Use tools like Postman or curl to interact with the API at

How does your code work?

    The code works through a structured architecture:
        - Server (server.js) acts as the main entry point that listens for requests
        - Routes direct incoming requests to the appropriate controllers
        - Controllers contain the business logic for handling student and course operations
        - Database stores all the information securely in MySQL tables
        - Each API endpoint corresponds to a specific operation (GET, POST, PUT, DELETE)

What can your project do?

       - Student Management: Create, read, update, and delete student records with details like name, email, course, and year level
       - Course Management: Manage courses with code, title, and units information
       - Data Validation: Ensure data integrity with unique email checks and required field validation
       - Error Handling: Provide clear error messages for various scenarios
       - RESTful Design: Follow standard API conventions for easy integration with frontend applications
       - Cross-Origin Support: Allow requests from different domains through CORS configuration
