# 🎬 Netflix Clone

<div align="center">
  
  > A modern Netflix-inspired streaming platform built with MERN stack and TMDB API
  
  [🌐 Live Demo]https://mernstackvideoplatform.onrender.com) | Response Time: ~800ms |  First 1 minute to start the server as it is deployed on free version of Render Deployment.
</div>

## 🌟 Key Features

### 🎥 Core Functionality
- TMDB API integration for movie data
- Zustand for state management
- Skeleton loading for better UX
- Response time optimization (800ms)


## 🚀 Getting Started

### Prerequisites
- Node.js
- MongoDB

### Installation
1. Clone the repository
```bash
git clone https://github.com/Naveen-Beniwal/Netflix-clone.git
Install backend dependencies
bash
cd Upgraded_Mern_Stack_Video_Platform
npm install
Install frontend dependencies
bash
cd frontend
npm install
Set up environment variables

Create a .env file in the root directory

Add the required environment variables

env
PORT=
MONGO_URI=
JWT_SECRET=
NODE_ENV=
TMDB_API_KEY=
CLIENT_URL=
ACTIVE_LINK=
Start the server
npm start
Start the frontend
bash
cd frontend

npm run dev
```
📄 API Endpoints

Authentication Routes

- POST /api/v1/auth/signup - Register new user
- POST /api/v1/auth/login - User login
- GET /api/v1/auth/logout - User logout

Protected Routes

- /api/v1/movie/* - Movie-related endpoints
- /api/v1/tv/* - TV show-related endpoints
- /api/v1/search/* - Search functionality endpoints
  
Search Routes

- GET /api/v1/search/movie/:query - Search movies
- GET /api/v1/search/tv/:query - Search TV shows
- GET /api/v1/search/person/:query - Search people
- GET /api/v1/search/history - Get user's search history

🎯 Learning Outcomes
Markdown
1. Self-Implemented Features:
   - Email verification system
   - Custom authentication
   - Skeleton loading

2. Best Practices:
   - Clean code principles
   - API integration
   - State management
   - Deployment strategies

3. Technical Skills:
   - Zustand over Redux
   - TMDB API integration
   - Render deployment
   - Performance optimization
  
  📞 Support
📧 naveenbeniwal00001@gmail.com
💻 GitHub

Built with 🎬 by Naveen Beniwal
Last Updated: 2024-01-26
