# HireStream - Job Portal & Recruitment Management System

HireStream is a job portal and recruitment management web application built for managing job postings, applications, candidate profiles, recruiting workflows, dashboards, and analytics.

## Overview

This project includes:
- a React + Vite frontend
- an Express backend
- SQLite-based database storage
- JWT authentication and role-based access
- job posting, application tracking, interview scheduling, and admin/recruiter dashboards

## Tech Stack

- Frontend: React.js, Vite, Tailwind CSS, Recharts, Lucide Icons
- Backend: Node.js, Express.js, JWT, bcryptjs
- Database: SQLite3

## Project Structure

```text
job-portal/
├── backend/
│   ├── src/
│   ├── uploads/
│   ├── .env
│   └── package.json
├── frontend/
│   ├── src/
│   ├── vite.config.js
│   ├── tailwind.config.js
│   └── package.json
├── README.md
├── package.json
└── package-lock.json
```

## Getting Started

### Prerequisites
- Node.js installed on your computer

### Install dependencies

```bash
cd backend
npm install

cd ../frontend
npm install
```

### Run the app

Backend:
```bash
cd backend
npm run dev
```

Frontend:
```bash
cd frontend
npm run dev
```

The app is designed to run locally with the backend on port 5000 and the frontend on port 3000.

## Demo Accounts

Password for all seeded demo accounts: `password123`

- Admin: `admin@jobportal.com`
- Recruiter: `recruiter@jobportal.com`
- Candidate: `candidate@jobportal.com`

## Notes

This repository combines the full project history with the GitHub remote initialization and serves as the source for the Job Portal application.
