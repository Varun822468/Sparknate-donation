# 🎁 Sparknate Donation

Live Site 👉 https://sparknate-donation-qpsd.vercel.app

Sparknate Donation is a full-stack donation platform where users can contribute to causes, and admins can create and manage donation campaigns. Built using the MERN stack with a clean UI and secure backend.

---

## 💡 Features

- 🙋 User registration and login (JWT Auth)
- 📝 Admin dashboard to add/manage causes
- 🧾 View all donation causes
- 📂 Category-wise browsing (e.g., Health, Education, Disaster Relief, etc.)
- 💳 Stripe payment integration (test mode)
- 📱 Fully responsive UI

---

## 🛠 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: JWT, Stripe API

---

## 📁 Project Structure

Sparknate-donation/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── server.js
│ └── .env (not pushed)
├── frontend/
│ ├── src/components/
│ ├── src/pages/
│ ├── App.jsx
│ └── main.jsx

yaml
Copy
Edit

---

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/vikask011/Sparknate-donation.git
cd Sparknate-donation
2. Setup Backend
bash
Copy
Edit
cd backend
npm install
# Add a .env file with required keys
npm start
🗝️ .env example:

ini
Copy
Edit
MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
3. Setup Frontend
bash
Copy
Edit
cd ../frontend
npm install
npm run dev


### **📦 Deployment**
Frontend: Vercel — sparknate-donation-qpsd.vercel.app

###** 🙌 Acknowledgements**
Stripe API

MongoDB

JWT.io

React + Tailwind community

