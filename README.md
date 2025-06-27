# Elite Edge Fitness Gym Application

## Project Overview

Elite Edge Fitness Gym Application is a full-stack web project designed to provide users with an interactive platform to explore gym plans, calculate BMI, view workout sessions, browse a gallery, check pricing plans, and contact the gym directly. The application features a modern, responsive UI and a backend for handling user messages via email.

## What I Did

- **Frontend Development:**  
  - Built a responsive and visually appealing frontend using React.
  - Developed modular, reusable components: Navbar, Hero Section, Workout Sessions, Gallery, Pricing, Contact Form, BMI Calculator, and Footer.
  - Used React Router for navigation and React Toastify for user notifications.
  - Styled the application with custom CSS for a clean and responsive design.

- **Backend Development:**  
  - Developed a Node.js/Express backend to handle contact form submissions.
  - Configured Nodemailer for sending emails securely using environment variables.
  - Set up CORS for secure cross-origin requests.

- **Integration:**  
  - Connected frontend and backend via REST API endpoints.

## Technologies Used

**Frontend:**
- React
- Vite
- React Router DOM
- React Toastify
- React Spinners
- Lucide React (icons)
- Axios
- CSS

**Backend:**
- Node.js
- Express
- Nodemailer
- dotenv
- CORS

## How It Works

- The application is structured with reusable components, each handling a specific section of the gym website.
- Users can navigate through the Navbar to view different sections: Hero, Workout Sessions, Gallery, Pricing, Contact, BMI Calculator, and Footer.
- The Contact form allows users to send messages, which are handled by the backend and sent via email.
- The BMI Calculator provides instant feedback based on user input.
- Toast notifications provide real-time feedback for user actions.
- The backend ensures secure handling of messages and email delivery.

## How to Run the Project

### Prerequisites

- Node.js and npm installed

### 1. Clone the Repository

```sh
git clone <your-repo-url>
cd GYM-APPLICATION-main
```

### 2. Setup and Run Backend

```sh
cd Backend
npm install
# Configure environment variables in config.env
npm run dev
```
The backend will start on port 4000.

### 3. Setup and Run Frontend

```sh
cd ../Frontend
npm install
npm run dev
```
The frontend will start on [http://localhost:5173](http://localhost:5173).

### 4. Usage

- Open [http://localhost:5173](http://localhost:5173) in your browser.
- Explore the gym plans, calculate your BMI, view the gallery, and contact the gym via the contact form.

---

You can now explore all the features of the Elite Edge Fitness Gym Application!
