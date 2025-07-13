#  Vistagram

A simple Instagram-like full-stack application that allows users to sign up, log in, upload them with captions, and view a timeline of all posts.

---

##  Features

- Add captions to posts
- View all posts in a timeline
- Like and Share posts
- JWT-based authentication
- Image upload via Cloudinary
- Frontend deployed on Netlify
- Backend deployed on Render
---

##  Tech Stack

-> Frontend (React)
- React.js (with Hooks)
- Axios for API requests

-> Backend (Node.js + Express)
- Express.js
- MongoDB + Mongoose
- JWT for authentication
- Cloudinary for image storage
- CORS and dotenv for environment/config

---


---

## Setup Instructions

###  Backend Setup

1. Go to `backend/` directory:

```bash
cd backend

2. Install Dependencies using npm install

3. Create .env file 

PORT=5000
MONGO_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JWT_SECRET=your_jwt_secret

4. Run the server using npm start

Frontend Setup

1. Go to frontend/ directory

cd frontend

2. Install Dependencies using npm install 

3. Create .env file 

REACT_APP_API_BASE_URL=http://localhost:5000/api

4. Start the react app using npm start






