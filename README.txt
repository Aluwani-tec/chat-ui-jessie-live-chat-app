React Chat Frontend (To Integrate With Python Backend)

📦 Features:
- Real-time chat using Socket.IO
- File/image attachment
- Search & unread message indicator
- Responsive design

🛠 Requirements:
- Node.js installed

🚀 How To Run:
1. Open terminal inside this folder.
2. Run: npm install
3. Run: npm start
4. App opens at: http://localhost:3000

💬 Socket Server:
- By default, connects to: http://localhost:5000
- You can change this inside src/App.js:
  const socket = io('http://localhost:5000');

📁 Folder Structure:
- src/data/users.json — user list
- src/App.js — main app logic
- src/App.css — styles