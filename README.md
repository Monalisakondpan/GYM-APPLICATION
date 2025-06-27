Project Story: Elite Edge Fitness Gym Application
Overview
Elite Edge Fitness Gym Application is a full-stack web project designed to provide users with an interactive platform to explore gym plans, calculate BMI, view workout sessions, browse a gallery, and contact the gym directly. The application features a modern, responsive UI and a robust backend for handling user messages via email.

What I Did
Frontend Development:
I built a responsive and visually appealing frontend using React. The UI includes sections for hero content, workout sessions, a gallery, pricing plans, a BMI calculator, and a contact form. I used React Router for navigation and React Toastify for user notifications.

Backend Development:
I developed a Node.js/Express backend to handle contact form submissions. The backend securely sends emails using Nodemailer and environment variables for sensitive configuration.

Integration:
The frontend and backend communicate via REST API endpoints, with CORS configured for secure cross-origin requests.

Styling:
I used CSS for custom styling, ensuring the application is user-friendly and works well on different devices.

Technologies Used
Frontend:

React
Vite
React Router DOM
React Toastify
React Spinners
Lucide React (icons)
Axios
Backend:

Node.js
Express
Nodemailer
dotenv
CORS

How to Run the Project
Prerequisites
Node.js and npm installed
1. Clone the Repository
   git clone <your-repo-url>
   cd GYM-APPLICATION-main

2. Setup and Run Backend
   cd Backend
npm install
# Configure environment variables in config.env
npm run dev

The backend will start on port 4000.

3. Setup and Run Frontend
   cd ../Frontend
   npm install
   npm run dev
The frontend will start on http://localhost:5173.
4. Usage
Open http://localhost:5173 in your browser.
Explore the gym plans, calculate your BMI, view the gallery, and contact the gym via the contact form.
