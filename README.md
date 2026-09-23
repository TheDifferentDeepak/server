# Portfolio Backend

Backend API for my portfolio website, built with Node.js, Express, and MongoDB.

## Live API
🔗 https://server-zw94.onrender.com

## Tech Stack
- Node.js
- Express
- MongoDB (Mongoose)

## Endpoints
- `POST /api/contact` — saves a contact form submission (name, email, message)

## How to Run Locally

1. Clone the repository
```bash
git clone https://github.com/TheDifferentDeepak/server.git
```

2. Install dependencies
```bash
cd server
npm install
```

3. Create a `.env` file with:

MONGO_URI=your_mongodb_connection_string
PORT=5000


4. Start server
```bash
npm run dev
```