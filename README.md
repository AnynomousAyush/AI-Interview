# AI-Powered Interview Preparation Tool

An intelligent interview preparation platform designed to help users practice technical interviews through AI-generated questions, explanations, and session management. The application provides personalized interview experiences based on role, experience level, and preferred topics.

## 🚀 Features

* 🔐 **User Authentication**

  * Secure registration and login using JWT authentication.
  * Protected routes and session management.

* 🤖 **AI-Powered Question Generation**

  * Generates interview questions and answers using the Gemini API.
  * Customizes questions based on:

    * Target role
    * Years of experience
    * Topics of interest

* 📚 **Concept Explanations**

  * Provides AI-generated explanations for interview questions.
  * Helps users understand underlying concepts more effectively.

* 📌 **Interview Session Management**

  * Create and manage interview preparation sessions.
  * Store generated questions for future review.
  * Track progress across multiple sessions.

* 📝 **Notes and Learning Support**

  * Save important insights and notes during preparation.
  * Revisit explanations and improve understanding.

* 📱 **Responsive User Interface**

  * Clean and intuitive design.
  * Optimized for desktop and mobile devices.

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Tokens (JWT)

### AI Integration

* Google Gemini API

## 📂 Project Structure

```
AI-Interview/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── utils/
│   └── package.json
│
└── README.md
```

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/AnynomousAyush/AI-Interview.git
cd AI-Interview
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend directory:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173
```

Start the backend server:

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```



