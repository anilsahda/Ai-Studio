# AI Studio Web App

A mini AI Studio web app built with **React + TypeScript + Node.js + SQLite** simulating fashion image generation.

## Features
- Signup & Login (JWT auth)
- Upload image (JPEG/PNG, max 10MB) & add prompt
- Simulated generation with 20% “Model overloaded” errors
- Retry and Abort functionality
- Recent 5 generations preview
- Responsive UI with accessibility support

## Tech Stack
- **Frontend:** React, TypeScript, TailwindCSS
- **Backend:** Node.js, Express, TypeScript, Prisma ORM
- **Database:** SQLite
- **Testing:** Jest, React Testing Library, Supertest, Vitest

## Setup & Run

### Backend
```bash
cd backend
npm install
npm run build
node dist/index.js

### Frontend
```bash
cd frontend
npm install
npm run dev

### Test
```bash
cd backend
npm test

cd frontend
npm test
