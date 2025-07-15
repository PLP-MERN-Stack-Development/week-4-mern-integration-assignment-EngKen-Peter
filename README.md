Week 4: MERN Stack Blog Application
Project Overview
This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) blog application built for the PLP Software Engineering Program. It allows users to create, view, and filter blog posts with categories. The application demonstrates backend-frontend integration, RESTful API communication, MongoDB usage, and React state management.

Directory Structure
bash
Copy
Edit
week-4-mern-integration-assignment-EngKen-Peter/
├── client/            # React front-end
├── server/            # Express + MongoDB backend
Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/PLP-MERN-Stack-Development/week-4-mern-integration-assignment-EngKen-Peter.git
cd week-4-mern-integration-assignment-EngKen-Peter
2. Server Setup
bash
Copy
Edit
cd server
npm install
Create a .env file based on the .env.example:

ini
Copy
Edit
PORT=5000
MONGO_URI=mongodb://localhost:27017/mern-blog
Start the server:

arduino
Copy
Edit
npm run dev
3. Client Setup
arduino
Copy
Edit
cd client
npm install
npm run dev
API Endpoints
Method	Endpoint	Description
GET	/api/posts	Get all blog posts
GET	/api/posts/:id	Get a specific blog post
POST	/api/posts	Create a new blog post
PUT	/api/posts/:id	Update a blog post
DELETE	/api/posts/:id	Delete a blog post
GET	/api/categories	Get all categories
POST	/api/categories	Create a new category

Features Implemented
View all blog posts

Create a new blog post

Filter posts by category

RESTful API integration

MongoDB schema for posts and categories

Environment variable configuration

Search and filter functionality

Responsive UI using Tailwind CSS

React state management with hooks

Screenshots
The following screenshots are included in the client/screenshots directory:

Homepage - Posts list

Create Post form

Post submission confirmation

MongoDB - Posts collection

MongoDB - Categories collection

Known Issues
Some posts may display "No content available" due to empty body fields or incomplete category data. Backend logic and API structure remain functional and correct.

Submission Checklist
GitHub Classroom repository used

Client and server directories are complete

.env.example files included

Screenshots added to the repository

Full documentation provided in this README file

Author
Kennedy Mbaluka Peter
Student - PLP MERN Stack Development Program