# RealtorIQ

RealtorIQ is a web-based platform designed to help real estate professionals streamline client acquisition and management. The system offers an intuitive dashboard with AI-powered insights, secure authentication, and automated workflows for managing leads, appointments, and property listings.

## Features

- **User Authentication:** Secure login with email/password and Google OAuth.
- **Client Management:** Submit client forms, import CSV data, and view client details.
- **Appointment Scheduling:** Select available time slots and confirm meetings.
- **AI Chatbot:** Integrated Botpress chatbot delivers market trends and insights.
- **Dashboard Overview:** Visual metrics on performance, leads, and property updates.

## Tech Stack

- **Backend:** Node.js, Express, PostgreSQL, Redis, Passport.js, and other supporting libraries.
- **Frontend:** React, React Router, Axios, and modern CSS.
- **Integrations:** Zapier for workflow automation and Botpress for natural language processing.

## Installation

### Prerequisites

- Node.js (>=14.x)
- PostgreSQL database
- Redis (recommended for production)
- npm or yarn

### Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/RealtorIQ.git
   cd RealtorIQ
   ```

2. **Backend Setup:**
- Navigate to the backend folder:
   ```bash
   cd backend
   ```

- Install dependencies:
   ```bash
   npm install
   ```

- Create a .env file and configure the necessary variables:

- Start the backend server:
   ```bash
   node server.js
   ```

2. **Frontend Setup:**
- Navigate to the frontend source folder:
   ```bash
   cd ../src
   ```

- Install dependencies:
   ```bash
   npm install
   ```

- Start the React development server:
   ```bash
   npm start
   ```

### Project Structure
   ```bash
    RealtorIQ/
    ├── backend/
    │   ├── server.js           # Express server & API endpoints
    │   └── ...                 # Other server-side modules and routes
    ├── src/
    │   ├── App.jsx             # Main React application entry
    │   ├── index.js            # ReactDOM rendering
    │   ├── components/         # Reusable React components (Auth, Form, Navbar, etc.)
    │   └── styles/             # Application styles
    ├── Capstone_Report_5.pdf   # Final engineering report for the project
    └── README.md               # This file
   ```

### Usage
- Open the frontend URL in your browser.
- Register or sign in as a realtor to access the dashboard.
- Use the dashboard to manage client leads, schedule appointments, and generate market reports.