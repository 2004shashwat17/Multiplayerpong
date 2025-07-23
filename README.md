THE PROJECT IS IN THE MASTER BRANCH !!!!!!👍🏻

🕹️ Pong Game – Single & Multiplayer Versions A modern reimagination of the classic Pong Game, built with real-time multiplayer support using Socket.IO, Node.js, and Canvas API. This project includes:

🎮 Version 1: Singleplayer Mode (Deployed on Netlify)

🤝 Version 2: Multiplayer Mode with WebSockets (Deployed on Render)

🔗 Live Demos 🎮 Singleplayer (v1) – Play on Netlify -> https://pongggg.netlify.app/

🤝 Multiplayer (v2) – Play on Render -> https://multiplayerpong.onrender.com/

🧠 Project Overview This full-stack web game demonstrates real-time communication using Socket.IO and interactive game rendering using Canvas API. The multiplayer version allows two players to connect, sync game state, and compete in real-time via WebSockets.

⚙️ Tech Stack Layer Tech Used Frontend HTML, CSS, JavaScript, Canvas API Backend Node.js, Express.js Real-Time Socket.IO (WebSockets) Hosting v1 Netlify Hosting v2 Render

🎯 Key Features ✅ Singleplayer (v1) Paddle controlled by user

AI-controlled opponent (basic)

Responsive design

Canvas rendering for smooth animations

🔄 Multiplayer (v2) Real-time two-player mode using Socket.IO

WebSocket-based communication with fallback to HTTP long polling

Uses .emit() and .on() for event messaging

Auto-reconnection support

Supports rooms for multiple games

🖼️ Canvas API in Action Renders 2D elements like paddles, ball, and score board

Smooth animations using requestAnimationFrame()

Pure JavaScript game logic, physics, and collision detection

🔌 Real-Time Communication (Socket.IO) Bi-directional: Real-time updates from client ↔ server

Event-driven: Custom events like playerMove, ballUpdate, etc.

Low-latency: Fast gameplay updates

Fallbacks: Gracefully switches to long-polling if WebSocket fails

Room Support: Isolated game sessions for different players

🚀 How to Run Locally

Clone the repository
git clone https://github.com/your-username/pong-game.git cd pong-game

Install backend dependencies
npm install

Start the server
node server/index.js

Open index.html in your browser (for singleplayer)
OR navigate to http://localhost:3000 (for multiplayer)
