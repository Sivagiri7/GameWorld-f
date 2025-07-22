🎮 GameWorld - Fullstack Website
GameWorld is a Fullstack Web Application where users can register, log in, and explore various game collections.
The website includes an Admin Panel to manage users and inquiries.

🛠️ Tech Stack
Frontend
React.js

React Router DOM

Axios

Tailwind CSS / Custom CSS

Backend
Spring Boot (Java)

RESTful API

MySQL / Railway Free Database

Deployment
Frontend: Netlify

Backend: Render / Railway

🌟 Features
User Panel
Responsive Design

Register & Login Functionality

Form submission with confirmation message

Protected Routes (Only logged-in users can access main content)

Admin Panel
View Registered Users

Delete Users

Manage Inquiries

🗄️ Database Structure
Table Name	Fields
users	id, name, email, password, role
inquiries	id, user_id, message, created_at

🚀 How to Run Locally
Frontend (React)
bash
Copy
Edit
cd frontend
npm install
npm start
Backend (Spring Boot)
bash
Copy
Edit
cd backend
mvn clean install
mvn spring-boot:run
Database
Use Railway / FreeSQLDatabase
