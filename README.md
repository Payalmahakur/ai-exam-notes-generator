<div align="center">

<img src="https://img.shields.io/badge/BCA%206th%20Semester-NSU%20Jamshedpur-1a6b4a?style=flat-square&labelColor=0f0f0f" />
<img src="https://img.shields.io/badge/Stack-MERN-1a6b4a?style=flat-square&labelColor=0f0f0f" />
<img src="https://img.shields.io/badge/AI-Google%20Gemini-1a6b4a?style=flat-square&labelColor=0f0f0f" />
<img src="https://img.shields.io/badge/Payments-Stripe-1a6b4a?style=flat-square&labelColor=0f0f0f" />
<img src="https://img.shields.io/badge/Auth-Firebase-1a6b4a?style=flat-square&labelColor=0f0f0f" />

<br/><br/>

# AI Exam Notes Generator

**An AI-powered SaaS web application that automatically generates structured, exam-oriented study notes using Google Gemini AI.**

*BCA 6th Semester Project — Netaji Subhas University, Jamshedpur (2023–2026)*

</div>

---

## About

Students enter a topic, class level, and exam type — the system produces comprehensive notes, block diagrams, charts, revision points, and exam-style questions tailored to their needs. All within minutes, powered by Google Gemini AI.

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

## Features

| # | Feature | Description |
|---|---|---|
| 01 | **AI Notes** | Comprehensive exam notes on any topic via Gemini AI |
| 02 | **Charts & Diagrams** | Auto-generated block diagrams, bar, pie & line charts |
| 03 | **Priority Revision Points** | 1-star, 2-star, 3-star importance levels for focused revision |
| 04 | **Exam Q&A Sets** | Short, long answer & diagram-based questions |
| 05 | **5-Min Revision Mode** | Condensed summary of the most important points |
| 06 | **Notes History** | All generated notes saved and accessible anytime |
| 07 | **PDF Download** | Download formatted PDF for offline study |
| 08 | **Credit System** | 100 free credits on sign-up; purchase more via Stripe |
| 09 | **Google Login** | Secure OAuth 2.0 authentication via Firebase |

---

## Tech Stack

### Frontend
- **React.js** — Single-page application UI with component-based architecture
- **Tailwind CSS** — Responsive styling with utility-first CSS
- **JavaScript (ES6+)** — Client-side logic and API communication
- **Recharts** — Bar, pie, and line chart rendering

### Backend
- **Node.js** — Server-side JavaScript runtime
- **Express.js** — RESTful API routing and middleware

### Database
- **MongoDB** (MongoDB Atlas) — NoSQL database for users, notes, and transactions

### Services
- **Google Gemini API** — AI-powered note, diagram, and chart generation
- **Firebase** — Google OAuth 2.0 authentication
- **Stripe** — Credit purchases with webhook support
- **Render** — Frontend and backend cloud deployment

### Development Tools
- VS Code · Git & GitHub · Postman · MongoDB Compass

---

## Database Structure

| Collection | Description |
|---|---|
| `users` | User profile, email and credit balance |
| `notes` | Generated notes with topic, content, diagrams and charts |
| `transactions` | Payment records and Stripe session data |
| `creditplans` | Available credit purchase plans and pricing |

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

## Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/ai-exam-notes-generator.git
cd ai-exam-notes-generator
```

### 2. Install dependencies

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

### 3. Set up environment variables

Create a `.env` file in the `/server` folder:

```env
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
FIREBASE_PROJECT_ID=your_firebase_project_id
```

### 4. Start the application

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

## References

- [React.js Documentation](https://reactjs.org)
- [Node.js Documentation](https://nodejs.org)
- [Express.js Documentation](https://expressjs.com)
- [MongoDB Documentation](https://mongodb.com/docs)
- [Google Gemini AI API](https://ai.google.dev)
- [Stripe Documentation](https://stripe.com/docs)
- [Firebase Documentation](https://firebase.google.com/docs)

---

<div align="center">

*Academic project — BCA programme, Netaji Subhas University, Jamshedpur*
&nbsp;·&nbsp;
*Academic use only*

</div>
