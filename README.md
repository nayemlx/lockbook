<h1>Lockbook</h1>

<h2>Description</h2>

<h3>This project is a Node.js backend social media application using Express.js, EJS for templating, MongoDB for the database, Passport.js for authentication, and Nodemailer for email handling. It provides a secure and functional backend with user authentication and email capabilities.
</h3>
Features

User registration and login with Passport.js.

Passwords securely hashed using bcrypt.

MongoDB for storing user data and other records.

Dynamic EJS templates for rendering pages.

Nodemailer integration for sending emails.

Installation

Prerequisites

Node.js and npm installed on your system.

MongoDB instance running locally or on a cloud provider.

Steps

Clone the repository:

git clone <repository-url>
cd <repository-folder>

Install dependencies:

npm install

Configure .env:

PORT=3000
MONGO_URI=mongodb://localhost:27017/your-database-name
SESSION_SECRET=your-session-secret
EMAIL_USER=your-email@example.com
EMAIL_PASS=your-email-password

Start MongoDB (if running locally):

mongod

Run the application:

npm start

Access the app at http://localhost:3000.

Project Structure

project-folder
├── public          # Static assets (CSS, JS, images)
├── routes          # API and application routes
├── views           # EJS templates
├── models          # Database schemas
├── config          # Configuration files
├── app.js          # Entry point of the app
├── package.json    # Metadata and dependencies
└── .env            # Environment variables

Useful Scripts

npm start: Start the server in production mode.

npm run dev: Start the server in development mode with hot reload (requires nodemon).

Dependencies

Major libraries and tools used:

Express.js: For creating routes and middleware.

EJS: For rendering dynamic HTML pages.

MongoDB/Mongoose: For database operations.

Passport.js: For secure authentication.

Nodemailer: For sending emails.

dotenv: For managing environment variables.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

License

This project is licensed under the MIT License.

