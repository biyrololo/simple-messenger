# simple-messenger
SimpleMessenger is a modern messenger application built with Python (FastAPI, SQLAlchemy), TypeScript (React), PostgreSQL, and WebSockets. It facilitates seamless communication between users with features like instant message delivery and a secure user interface.

# Features
- FastAPI and SQLAlchemy: Utilizes FastAPI for a high-performance web server and SQLAlchemy for interacting with the PostgreSQL database.

- WebSocket: Implements WebSocket technology for real-time message delivery, ensuring instant responsiveness to new messages.

- React and TypeScript: The frontend is developed using React and TypeScript, providing clear data typing and enhancing code security.

- Security: Implements security measures such as password hashing, authorization checks, and other safeguards to ensure data confidentiality.

- User-friendly Interface: Offers a simple and intuitive user interface for a convenient messaging experience.

# Tech Stack
Backend
- FastAPI for the web server.
- SQLAlchemy for interacting with the PostgreSQL database.
- WebSockets for real-time message transmission.
  
Frontend
- React for building the user interface.
- TypeScript for clear data typing and enhanced code safety.
Database
- PostgreSQL for storing user data and messages.
  
# Installation and Usage
1. Install dependencies with `pip install fastapi sqlalchemy pydantic` for the backend and `npm install` for the frontend.
2. Set up the PostgreSQL database and specify connection parameters in the configuration file.
3. Run the backend with `uvicorn server:app --reload`.
4. Start the frontend with `npm start`.
5. Open a browser and navigate to `http://localhost:3000` to use SimpleMessenger

# Quick Start

```
cd server
# Install backend dependencies
pip install fastapi sqlalchemy pydantic

# Run backend
uvicorn server:app --reload
```

```
cd client
# Install frontend dependencies
npm install

# Run frontend
npm start
```

Visit `http://localhost:3000` in your browser to access SimpleMessenger.

# License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.
