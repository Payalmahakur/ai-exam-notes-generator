# AI Exam Notes Generator

> An AI-powered web application that automatically generates structured, exam-oriented study notes for students using Google Gemini AI.

A BCA 6th Semester Project — Netaji Subhas University, Jamshedpur (2023–2026)

---

## Project Details

| Field | Details |
|---|---|
| Project Title | AI Exam Notes Generator |
| Degree | Bachelor of Computer Applications (BCA) |
| Academic Session | 2023 – 2026 |
| University | Netaji Subhas University, Jamshedpur |
| Department | Computer Applications |
| Guide | Mr. Ritesh Kumar Jha (Assistant Professor, CS & IT) |

### Submitted By

| Name | Registration No. | Section |
|---|---|---|
| Tanushree Dutta | NSU2303265 | B |
| Payal Mahakur | NSU2303163 | A |

---

## About the Project

The AI Exam Notes Generator is a web-based SaaS application that leverages Artificial Intelligence to automatically generate structured, exam-oriented study notes for students. Built using the **MERN Stack** and integrated with the **Google Gemini AI API**, the platform produces high-quality notes, diagrams, charts and revision points based on any topic provided by the user.

Students simply enter a topic, their class level and their examination type — and the system automatically produces comprehensive notes tailored to their needs.

---

## Features

- **AI-Powered Notes** — Generate comprehensive exam notes on any topic instantly using Google Gemini AI
- **Exam Customization** — Supports CBSE, AKTU and other examination boards
- **Visual Content** — Auto-generates block diagrams, bar charts, pie charts and line charts
- **Revision Points** — Priority-based revision points with 1-star, 2-star and 3-star importance levels
- **Question Sets** — Short answer, long answer and diagram-based questions
- **Quick Revision Mode** — 5-minute revision summary of the most important points
- **Notes History** — All previously generated notes saved and accessible anytime
- **PDF Download** — Download generated notes as formatted PDF documents for offline study
- **Credit System** — 100 free credits on registration; additional credits purchasable via Stripe
- **Secure Login** — Google OAuth 2.0 authentication via Firebase

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- JavaScript (ES6+)
- Recharts (for data visualization)

### Backend
- Node.js
- Express.js

### Database
- MongoDB (MongoDB Atlas for cloud hosting)

### AI Integration
- Google Gemini API

### Authentication
- Firebase (Google OAuth 2.0)

### Payment Gateway
- Stripe (with webhook support)

### Deployment
- Render (Frontend + Backend)

### Development Tools
- VS Code
- Git & GitHub
- Postman
- MongoDB Compass

---

## System Requirements

### Hardware
- Processor: Intel Core i3 or higher
- RAM: Minimum 4 GB (Recommended: 8 GB)
- Storage: Minimum 20 GB free space
- Stable Internet Connection

### Software
- Node.js v18 or higher
- MongoDB (local or Atlas)
- Modern Web Browser (Chrome / Firefox / Edge)

---

## How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/ai-exam-notes-generator.git
cd ai-exam-notes-generator
```

### 2. Install Dependencies

**Backend:**
```bash
cd server
npm install
```

**Frontend:**
```bash
cd client
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the `/server` folder:
```
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
FIREBASE_PROJECT_ID=your_firebase_project_id
```

### 4. Start the Application

**Backend:**
```bash
cd server
npm start
```

**Frontend:**
```bash
cd client
npm start
```

The app will run at `http://localhost:3000`

---

## Database Structure

The MongoDB database contains 4 collections:

| Collection | Description |
|---|---|
| `users` | Stores user profile, email and credit balance |
| `notes` | Stores all generated notes with topic, content, diagrams and charts |
| `transactions` | Stores payment records and Stripe session data |
| `creditplans` | Stores available credit purchase plans |

---

## Project Synopsis

This project was submitted as a Project Synopsis for the partial fulfillment of the requirement for the degree of Bachelor of Computer Applications (BCA) at Netaji Subhas University, Jamshedpur for the Academic Session 2023–2026.

---

## References

- [React.js Documentation](https://reactjs.org)
- [Node.js Documentation](https://nodejs.org)
- [Express.js Documentation](https://expressjs.com)
- [MongoDB Documentation](https://mongodb.com/docs)
- [Google Gemini AI API](https://ai.google.dev)
- [Stripe Documentation](https://stripe.com/docs)
- [Firebase Documentation](https://firebase.google.com/docs)

---

## License

This project is developed for academic purposes as part of the BCA program at Netaji Subhas University, Jamshedpur.
