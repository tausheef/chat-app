📚 Table of Contents
About

Features

Tech Stack

Screenshots

Installation

Usage

Authentication

Folder Structure

Contributing

License

📖 About
A full-stack real-time chat application built with the MERN stack, featuring Socket.io for live messaging and Passport.js for social login (Google & GitHub). Designed to mimic modern chat experiences like WhatsApp or Slack.

✨ Features
🔐 Google and GitHub OAuth authentication

💬 Real-time private messaging using Socket.io

🧑‍🤝‍🧑 Online users tracking

🔔 Typing indicators

📱 Responsive UI

🗃️ MongoDB database integration

🔒 Password hashing with bcrypt (if applicable)

🛠️ Tech Stack
Frontend:

React

Socket.io-client

Axios

TailwindCSS / CSS / Bootstrap (mention what you used)

Backend:

Node.js

Express.js

MongoDB + Mongoose

Socket.io

🧑‍💻 Installation
1. Clone the repo:
bash
Copy
Edit
git clone https://github.com/tauseefraza/chat-app.git
cd chat-app
2. Backend Setup
bash
Copy
Edit
cd backend
npm install
cp .env.example .env # Add your Mongo URI, OAuth keys
npm start
3. Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
🔐 Authentication
Uses Passport.js strategies:

✅ Google OAuth

✅ GitHub OAuth

After login, user is redirected to the chat room

📁 Folder Structure
arduino
Copy
Edit
chat-app/
│
├── backend/
│   ├── config/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── sockets/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   └── App.js
│   └── public/
│
└── README.md
🤝 Contributing
Contributions are welcome! Feel free to fork this repo, open issues, or submit pull requests.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙋‍♂️ Author
Tauseef Raza
📧 Tausheef Raza
💼 https://www.linkedin.com/in/tausheef-raza/
