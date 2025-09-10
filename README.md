👇

🚀 QuickGPT – AI Chatbot (MERN Stack)

QuickGPT is an AI-powered chatbot built with the MERN stack (MongoDB, Express, React, Node.js), designed to work like ChatGPT. It allows users to chat with AI, generate images, and purchase credits. The project is fully deployed on Vercel.

🌟 Features

💬 AI Chat – Real-time conversation with AI

🖼️ Image Generation – Create AI-generated images

👥 Community – View published images from other users

💳 Credits System – Buy credits via integrated payment gateway

🔐 Authentication – Secure user login & signup with JWT

📊 Responsive UI – Modern React + TailwindCSS frontend

☁️ Deployment – Hosted on Vercel

🛠️ Tech Stack

Frontend: React, TailwindCSS, React Router, Axios
Backend: Node.js, Express.js, JWT Authentication
Database: MongoDB (Mongoose ORM)
AI Integration: OpenAI API (Chat + Images)
Deployment: Vercel (Frontend + Backend)

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/amitraj-2312/quickgpt.git
cd quickgpt

2️⃣ Install dependencies
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install

3️⃣ Setup Environment Variables

Create a .env file in the server folder with:

JWT_SECRET = 'gs#secret'


MONGODB_URI = mongodb+srv://amitjhastm2001_db_user:amit12345@cluster0.jtewbva.mongodb.net

GEMINI_API_KEY = AIzaSyCnb-Xu9wrf1dWaVr_eUyFwF2VTr-6yzfE

#ImageKit
IMAGEKIT_PUBLIC_KEY ='public_7pTN3IJvVy49qGMvirtPPQ7z2V0='
IMAGEKIT_PRIVATE_KEY = 'private_YdpE5U/gQvV0bX40d8VqTBV9iQo='
IMAGEKIT_URL_ENDPOINT = 'https://ik.imagekit.io/yd0ypbonz'

#Stripe
STRIPE_PUBLISHABLE_KEY =pk_test_51RyvUj34zGbs0E6bQ0rujivB6DwnQj5Q8pVZasH3AcEfTRVEcdRHaL3zcfmlEDZdj7jusOpFRnbCfr8bmJSThxtB00xG59MPiJ
STRIPE_SECRET_KEY = sk_test_51RyvUj34zGbs0E6bZwFRhphDzPqIlOPuSXfWNmZbkHe2TxJgX3irXkPmBujDtMNthmw7sNEPJFP6n1mVkdpOIdgG00QrIc7REK

STRIPE_WEBHOOK_SECRET = whsec_9jqozSYFRYZyR1ov262JhmENcSepkp2W

4️⃣ Run the app locally
# Run backend
cd server
npm run server

# Run frontend
cd ../client
npm run dev

🌍 Live Demo
https://quick-gpt-vert.vercel.app/

