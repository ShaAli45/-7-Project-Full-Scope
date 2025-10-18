
🎭 Meme Marketplace Platform
A full-stack web application that connects brands with influencers for meme-based marketing campaigns.
This platform enables brands to create promotional campaigns and influencers to apply for these opportunities — fostering a collaborative ecosystem for viral, community-driven marketing.

🚀 Features
👩‍💼 For Brands
•	User Authentication – Secure signup & login with JWT
•	Campaign Management – Create, edit, and manage promotions
•	Influencer Discovery – Browse & search verified influencers
•	Application Review – Review and approve influencer applications
•	Real-time Messaging – Chat directly with influencers
•	Analytics Dashboard – Monitor campaign performance and engagement
👨‍🎤 For Influencers
•	Profile Management – Create rich profiles with social links
•	Portfolio Showcase – Display work samples and past collaborations
•	Campaign Applications – Apply to available brand campaigns
•	Pricing Management – Manage service rates and offerings
•	Verification System – Gain verified status for credibility
•	Messaging System – Chat directly with brands
⚙️ Technical Highlights
•	Responsive Design – Tailwind CSS mobile-first layout
•	Real-time Updates – Notifications and messaging
•	File Uploads – Image, video & document uploads via Cloudinary
•	Secure Authentication – JWT + bcrypt password hashing
•	RESTful API – Modular and scalable backend architecture

🛠️ Tech Stack
Frontend
•	⚛️ React 19
•	🎨 Tailwind CSS
•	🔗 React Router DOM
•	🌐 Axios
•	💫 Framer Motion
•	🔔 React Hot Toast
•	🧩 Lucide React
•	⚡ Vite
Backend
•	🟢 Node.js + Express.js
•	🍃 MongoDB + Mongoose
•	🔐 JWT + bcryptjs
•	☁️ Cloudinary + Multer
•	🌍 CORS Middleware

📋 Prerequisites
Ensure the following are installed before setup:
•	Node.js (v16 or higher)
•	npm or yarn
•	MongoDB (local or MongoDB Atlas)
•	Cloudinary account (for media uploads)

🔧 Installation & Setup
2️⃣ Backend Setup
cd backend
npm install
Create a .env file in the backend/ directory:
# Database
MONGODB_URI=mongodb://localhost:27017/meme_project
# or use MongoDB Atlas
# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/meme_project
# JWT Secret
JWT_SECRET=your_jwt_secret_key_here

# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Server
PORT=5000
NODE_ENV=development
3️⃣ Frontend Setup
cd ../frontend
npm install
Create a .env file in the frontend/ directory:
VITE_API_URL=http://localhost:5000/api
4️⃣ Database Setup
Ensure MongoDB is running locally or connected via Atlas.

🚀 Running the Application
Development Mode
Start Backend
cd backend
npm run dev
Server will run on: http://localhost:5000
Start Frontend
cd frontend
npm run dev
App will run on: http://localhost:5173
Production Mode
# Build frontend
cd frontend
npm run build

# Start backend
cd ../backend
npm start

