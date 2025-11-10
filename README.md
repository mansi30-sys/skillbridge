**SkillBridge**
A simple e-learning web app built with Node.js, Express.js, MongoDB, and HTML/CSS/JavaScript.
Users can register, log in, learn from lessons, and take quizzes.

**Features**

1) User registration & login (stored in MongoDB)

2) Lessons with videos & images

3) Linked quizzes for each lesson

4) Score display after each quiz

5) Responsive and easy-to-use UI

**Tech Stack**

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB

**How to Run** 
1) Clone the repo
git clone https://github.com/mansi30-sys/skillbridge.git
cd skillbridge

2) Install dependencies
npm install

3) Create a .env file
MONGO_URI=mongodb://127.0.0.1:27017/skillbridge
JWT_SECRET=yourSecretKey
PORT=3000

4) Run the server
node backend/server.js

5) Open in browser → http://localhost:3000
