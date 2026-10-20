# TravelEase ✈️

**A Full-Stack Travel & Rental Booking Platform**

TravelEase is a web application designed to simplify the travel and rental experience. It brings together accommodation discovery, car rentals, booking workflows, user accounts, and payment processing in one platform.

The project uses a separate frontend and backend to provide a modular foundation for its user-facing features and administrative functionality.

## ✨ Features

- 🏨 **Accommodation Discovery** — Explore hotels and rental properties.
- 🚗 **Car Rentals** — Browse available vehicles.
- 🔐 **Authentication** — User registration, login, and account verification.
- 👤 **User Profiles** — Access profile and account-related features.
- 🏡 **Property Hosting** — Interfaces for submitting rental properties.
- 📅 **Booking Management** — Backend functionality for booking operations.
- 💳 **Payment Integration** — Stripe integration for payment processing.
- 🔔 **Notifications** — Dedicated notification functionality.
- 🛠️ **Administration** — Separate admin authentication and dashboard.
- 🛡️ **Security Middleware** — Request validation, rate limiting, and HTTP security protections.

## 🛠️ Tech Stack

### Frontend

- React
- Vite
- React Router
- Axios
- Tailwind CSS
- React Icons

### Backend

- Node.js
- Express.js
- MongoDB / Mongoose
- PostgreSQL client
- Supabase client
- JWT
- Passport.js
- Google OAuth 2.0
- Stripe
- Nodemailer

### Security

- Helmet
- Express Rate Limit
- Express Validator
- Cookie Parser
- Express Session
- Input sanitization middleware

## 📁 Project Structure

```text
TravelEase/
├── backend/
│   ├── config/
│   ├── Database/
│   ├── middleware/
│   ├── routes/
│   ├── app.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── package.json
│
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm
- Access to the database and external services required by the application

### 1. Clone the repository

```bash
git clone https://github.com/0xsila/project2cp.git
cd project2cp
```

### 2. Install backend dependencies

```bash
cd backend
npm install
```

Configure the required environment variables according to the backend configuration and application code.

### 3. Start the backend

```bash
npm run dev
```

If the development script is unavailable, check `backend/package.json` for the supported start command.

### 4. Install frontend dependencies

Open another terminal:

```bash
cd frontend
npm install
```

Configure the frontend API base URL to point to your backend.

### 5. Start the frontend

```bash
npm run dev
```

Open the local URL displayed by Vite in your terminal.

## 🔑 Configuration

TravelEase integrates with external services that may require environment variables, depending on the features enabled in the application.

Typical configuration categories include:

- Database connection
- Server port
- Authentication and session secrets
- Google OAuth credentials
- Frontend origin and API URL
- Stripe API credentials
- Email service configuration

Use the variable names expected by the application code. Keep credentials in local environment files and never commit secrets to the repository.

## 🛡️ Security Considerations

The backend includes security middleware for protecting HTTP requests and validating input. Before deploying the application, ensure that:

- Authentication and authorization are enforced on the server.
- Sensitive configuration is stored securely.
- Payment events are verified before being trusted.
- File uploads and user inputs are validated.
- CORS and cookie settings are configured for the deployment environment.
- Database access follows the principle of least privilege.

## 👨‍💻 Author

**Sila Yahia — 0xsila**

- GitHub: [@0xsila](https://github.com/0xsila)
- HackerOne: [@0xsila](https://hackerone.com/0xsila)
- TryHackMe: [@0xsila](https://tryhackme.com/p/0xsila)
- LinkedIn: [linkedin.com/in/0xsila](https://www.linkedin.com/in/0xsila/)

---

*TravelEase — Making travel and rentals easier, in one place.* ✈️
