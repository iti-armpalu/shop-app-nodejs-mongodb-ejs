**1. Project details**

The project is a web shop application built with Node.js, Express, and Mongoose, utilizing EJS (Embedded JavaScript) for server-side rendering of dynamic views. It features a powerful backend for managing data with MongoDB via Mongoose, combined with EJS templates to generate HTML content dynamically, providing a seamless user experience.

**2. Technologies used**

**--- Backend and frontend setup ---**

**Node.js:** Node.js was chosen as the runtime environment for the project due to its asynchronous and event-driven architecture, making it well-suited for building scalable and efficient server-side applications.

**Express:** Express.js, a minimalist web framework for Node.js, was employed to simplify the process of building robust and flexible web applications, providing a wide range of features for handling HTTP requests and routing.

**MongoDB:** a NoSQL database, was chosen for its flexibility and scalability, enabling the storage of unstructured data and accommodating the evolving needs of the project without requiring a predefined schema.

**EJS (Embedded JavaScript):** EJS templating engine was chosen for server-side rendering of dynamic views, allowing for the seamless integration of JavaScript code into HTML templates, enhancing code readability and maintainability while facilitating the generation of dynamic content.

***--- Additional packages ---**

Authentication and Security:
  -Bcryptjs: Utilized for securely hashing passwords before storing them in the database, enhancing security by protecting user credentials.

Session Management:
  -Connect-mongodb-session: Integrated as a session store for MongoDB with Express sessions, facilitating session management in the application.
  -Connect-flash: Used for displaying temporary messages to users, such as success or error notifications after certain actions.

Middleware and Server-side Logic:
  -Body-parser: Employed to parse incoming request bodies in Express.js, simplifying data extraction from HTTP requests.
  -Cookie-parser: Used as middleware to parse cookies in Express.js, enabling the extraction of cookie data from incoming requests.
  -Csrf-csrf: Implemented for cross-site request forgery (CSRF) protection in Express.js, enhancing the security of the application against CSRF attacks.
  -Dotenv: Incorporated to load environment variables from a .env file into process.env, providing a convenient way to manage configuration settings.
  -Express-session: Integrated for managing sessions in Express.js, facilitating session-based authentication and user state management.

Database and ORM:
  -Mongoose: Mongoose, an object data modeling (ODM) library for MongoDB and Node.js, was utilized to facilitate interaction with the MongoDB database, enabling schema-based modeling and validation of data, and simplifying database operations.

User Input Validation:
  -Express-validator: Employed for input validation in Express.js, ensuring data integrity and security by validating user input before processing.

File Upload & Download and Email Handling:
  -Multer: Utilized as middleware for handling multipart/form-data (file uploads) in Express.js, enabling file upload functionality in the application.
  -Nodemailer: Integrated for sending emails with Node.js, enabling transactional email functionality such as user registration confirmation and password reset.
  -Nodemailer-sendgrid-transport: Employed as a transport module for sending emails via SendGrid with Nodemailer, offering a convenient way to send emails using the SendGrid email delivery service.
  -Pdfkit: Utilized as a PDF generation library for Node.js, enabling the generation of dynamic PDF documents based on application data.

Payment Processing:
  -Stripe: Employed as the Stripe API client for Node.js, enabling payment processing and management of subscriptions in the application.


3: Start the project:

Step 1: Install all the dependencies listed in the "package.json" with "npm install"
Step 2: Start the development server with "nodemon app.js."












