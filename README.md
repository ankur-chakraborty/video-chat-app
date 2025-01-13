# Video Conferencing App

A real-time video conferencing application built using **WebRTC**, **Socket.io**, **Peer.js**, and **Node.js**. This app allows users to connect to a video call room, share audio/video streams, and chat in real time.

## Features
- **Video and Audio Streaming**: High-quality video and audio communication using WebRTC.
- **Real-Time Chat**: Send and receive instant text messages during the call.
- **Dynamic Room Creation**: Automatically generates unique room IDs using UUID for each meeting.
- **Responsive UI**: Built using **Tailwind CSS** for a modern and responsive interface.
- **Mute and Video Toggle**: Options to mute/unmute audio and enable/disable video.
- **Invite Link**: Shareable room links for easy collaboration.
- **Simple Backend**: Powered by **Node.js** and **Express.js**.
- **Secure Connections**: Uses Peer.js for peer-to-peer communication.

## Tech Stack
### Frontend:
- **HTML**, **CSS** (Tailwind CSS), **JavaScript**
- **WebRTC** for audio/video streaming
- **Peer.js** for handling WebRTC connections

### Backend:
- **Node.js** and **Express.js** for server-side logic
- **Socket.io** for real-time communication
- **UUID** for generating unique room IDs

### Deployment:
- Works locally and can be deployed on platforms like Heroku, Vercel, or any Node.js-compatible hosting service.

### File Structure
.
├── public/             # Static files (CSS, JavaScript, etc.)
│   ├── script.js       # Frontend logic
│   └── style.css       # Optional custom styles
├── views/              # EJS templates
│   └── room.ejs        # HTML structure for video rooms
├── server.js           # Backend server logic
└── package.json        # Project configuration and dependencies
