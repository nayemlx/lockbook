<h1 style='font-size:50px;'>LockBook</h1>

 <h2>Description</h2>
    <p>This project is a Node.js backend application using Express.js, EJS for templating, MongoDB for the database, Passport.js for authentication, and Nodemailer for email handling. It provides a secure and functional backend with user authentication and email capabilities.</p>

<h2>Features</h2>
    <ul>
        <li>User registration and login with Passport.js.</li>
        <li>Passwords securely hashed using bcrypt.</li>
        <li>MongoDB for storing user data and other records.</li>
        <li>Dynamic EJS templates for rendering pages.</li>
        <li>Nodemailer integration for sending emails.</li>
    </ul>

 <h2>Installation</h2>

   <h3>Prerequisites</h3>
    <ul>
        <li>Node.js and npm installed on your system.</li>
        <li>MongoDB instance running locally or on a cloud provider.</li>
    </ul>

<h3>Steps</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone &lt;repository-url&gt;
            <h2>Project Structure</h2>
    <pre><code>project-folder

   <h2>Installation</h2>

<h3>Steps</h3>
<ol>
    <li>Clone the repository:
        <pre><code>git clone &lt;repository-url&gt;
    </li>
    <li>Navigate to the repository folder:
        <pre><code>cd &lt;repository-folder&gt;
    </li>
    <li>Install dependencies:
        <pre><code>npm install
    </li>
    <li>Configure <code>.env</code> file with the following values:
        <pre><code>PORT=3000
MONGO_URI=mongodb://localhost:27017/your-database-name
SESSION_SECRET=your-session-secret
EMAIL_USER=your-email@example.com
EMAIL_PASS=your-email-password
    </li>
    <li>Start MongoDB (if running locally):
        <pre><code>mongod
    </li>
    <li>Run the application:
        <pre><code>npm start
    </li>
</ol>
<p>Access the app at <a href="http://localhost:3000">http://localhost:3000</a>.</p>

<h2>Project Structure</h2>
<pre><code>project-folder
├── public          # Static assets (CSS, JS, images)
├── routes          # API and application routes
├── views           # EJS templates
├── models          # Database schemas
├── config          # Configuration files
├── app.js          # Entry point of the app
├── package.json    # Metadata and dependencies
└── .env            # Environment variables


<h2>Installation</h2>

<h3>Steps</h3>
<ol>
    <li>Clone the repository:
        <pre><code>git clone &lt;repository-url&gt;</code></pre>
    </li>
    <li>Navigate to the repository folder:
        <pre><code>cd &lt;repository-folder&gt;</code></pre>
    </li>
    <li>Install dependencies:
        <pre><code>npm install</code></pre>
    </li>
    <li>Configure <code>.env</code> file with the following values:
        <pre><code>PORT=3000
MONGO_URI=mongodb://localhost:27017/your-database-name
SESSION_SECRET=your-session-secret
EMAIL_USER=your-email@example.com
EMAIL_PASS=your-email-password</code></pre>
    </li>
    <li>Start MongoDB (if running locally):
        <pre><code>mongod</code></pre>
    </li>
    <li>Run the application:
        <pre><code>npm start</code></pre>
    </li>
</ol>
<p>Access the app at <a href="http://localhost:3000">http://localhost:3000</a>.</p>



<h2>Useful Scripts</h2>
    <ul>
        <li><code>npm start</code>: Start the server in production mode.</li>
        <li><code>npm run dev</code>: Start the server in development mode with hot reload (requires nodemon).</li>
    </ul>

 <h2>Dependencies</h2>
    <p>Major libraries and tools used:</p>
    <ul>
        <li>Express.js: For creating routes and middleware.</li>
        <li>EJS: For rendering dynamic HTML pages.</li>
        <li>MongoDB/Mongoose: For database operations.</li>
        <li>Passport.js: For secure authentication.</li>
        <li>Nodemailer: For sending emails.</li>
        <li>dotenv: For managing environment variables.</li>
    </ul>

 <h2>Contributing</h2>
    <p>Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.</p>

<h2>License</h2>
    <p>This project is licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</p>
</div>
