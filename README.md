# 🏠 HouseHunt | Full-Stack Rental Marketplace

**HouseHunt** is a modern MERN stack application designed to simplify the process of finding and listing rental properties. This platform bridges the gap between property owners, agents, and home seekers by providing a secure, filtered, and user-friendly environment to discover the perfect home.

---

## 🌟 Key Features

* **Secure Authentication:** User registration and protected login powered by JWT (JSON Web Tokens) and bcrypt password hashing.

* **Smart Discovery & Filters:**
  * **Location Search:** Find homes in specific areas using text search.
  * **Price Range:** Set minimum and maximum budgets.
  * **Property Specs:** Filter by BHK configuration and property type (Apartment, House, etc.).
  * **Status Toggles:** Sort listings by "Furnished" status or source (Owner, Dealer, or Builder).

* **Listing Management:** Authenticated users can create, update, and remove their own property advertisements.

* **Detailed Insights:** Support for image URLs, detailed descriptions, and direct access to the poster's information.

* **Adaptive UI:** Fully responsive design built to work seamlessly across desktops, tablets, and mobile devices.

---

## 💻 Technical Stack

### **Backend (The Engine)**

* Node.js  
* Express.js  
* MongoDB  
* Mongoose  
* JWT Authentication  
* bcryptjs  
* dotenv  
* cors  

### **Frontend (The Interface)**

* React.js  
* React Hooks  
* Axios  
* CSS  

### **Development & Tools**

* Nodemon  
* Postman  
* Git & GitHub  

---

## 📂 Project Structure
house-hunt-mern/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ └── server.js
│
└── frontend/
├── public/
├── src/
│ ├── components/
│ ├── services/
│ ├── App.js
│ └── index.js

---

## ⚙ Installation & Setup

### Backend Setup
cd backend
npm install

Create a `.env` file inside the backend directory:
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

---

### Frontend Setup
cd frontend
npm install

Ensure the proxy is configured in `frontend/package.json`:
"proxy": "http://localhost:5001"

---

## ▶ Running the Application

### Start Backend
cd backend
npm run server

Backend runs at:  
http://localhost:5001  

### Start Frontend
cd frontend
npm start

Frontend runs at:  
http://localhost:3000  

---

## 🌱 Seeding Sample Data

To populate the database:
cd backend
npm run seed

To destroy all data:
npm run seed:destroy
