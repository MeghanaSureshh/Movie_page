# Movie_page
# 🎬 MovieHub

MovieHub is a **MERN stack based Movie Review Platform** where users can explore movies, see featured movies, get recommendations, and add reviews.  
Admins have a separate dashboard to manage movies.  

---

## 🚀 Features

- 🌟 **Featured Movies Section** – Highlight trending movies  
- 🎯 **Recommended for You Section** – Personalized recommendations  
- 🔐 **Authentication** – Login & Logout functionality using JWT  
- 🖼 **Movie Posters** – Display images of movies  
- 🎨 **Dark/Light Mode** toggle for better UI experience  
- 🛠 **Admin Dashboard** – Manage movie details, add/remove movies  
- 💬 **User Reviews** – Users can leave feedback on movies  

--

## 🛠️ Tech Stack

**Frontend**: React.js, React Router, CSS  
**Backend**: Node.js, Express.js  
**Database**: MongoDB (Mongoose ODM)  
**Auth**: JWT (JSON Web Tokens)  

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

cd Movie_page

Backend Setup:
cd backend
npm install
npm start

Frontend Setup:
cd frontend
npm install
npm start


.env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000


project Structure 

moviehub/
│── backend/         # Node.js + Express backend
│   ├── models/      # MongoDB models
│   ├── routes/      # API routes
│   ├── controllers/ # Logic for API
│   └── server.js    # Entry point
│
│── frontend/        # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│
└── README.md

Admin Credentials:_

Email: meghana@moviehub.com
Password: 12345  

For User:-
*First register and Login.



