# Zerodha Dashboard 📊

**A React-based trading dashboard for viewing holdings, positions, and orders.**

This repository contains the **dashboard application** of a Zerodha clone. It focuses on the authenticated user experience, displaying trading data such as holdings, open positions, and placed orders by consuming a backend API.

The dashboard is part of a larger **full-stack MERN project**, with the backend deployed separately and responsible for authentication and data persistence.

---

## 🧠 About

The Zerodha Dashboard is designed to replicate the core trading dashboard experience of Zerodha. It fetches real-time data from a backend service and presents it in a clean, tabular, and visual format.

This project emphasizes:
- Real-world API integration
- Production-ready React patterns
- Defensive data handling for deployed environments

---

## 📦 Features

✔ Dashboard view for holdings, positions, and orders  
✔ Data fetched dynamically from MongoDB via backend APIs  
✔ Axios-based API integration  
✔ Environment variable support for backend URL  
✔ Clean table-based UI with calculated metrics  

---

## 🧰 Tech Stack

- **React** (Create React App)
- **Axios** for API requests
- **CSS** for styling
- Deployed on **Vercel**

---

## 🗂 Folder Structure
zerodha-dashboard/
├─ public/
├─ src/
│ ├─ components/
│ ├─ pages/
│ ├─ App.js
│ ├─ index.js
│ └─ styles/
├─ .gitignore
├─ package.json
└─ README.md


---

## 🚀 Getting Started

Follow these steps to run the dashboard locally.

### 1. Clone the repository
-bash
git clone https://github.com/pra90mathur/zerodha-dashboard.git
cd zerodha-dashboard

2. Install dependencies
npm install

3. Configure environment variables

Create a .env file in the root directory:

REACT_APP_BACKEND_URL=https://zerodha-backend-gs2t.onrender.com


⚠️ Do not commit the .env file to GitHub.

4. Start the development server
npm start


The app will run at: http://localhost:3000

🔌 Backend Integration

This dashboard expects a backend API that exposes routes such as:

GET /holdings
GET /positions
GET /orders


Ensure the backend server is running and accessible at the URL specified in REACT_APP_BACKEND_URL.

📁 Deployment

The dashboard is deployed on Vercel.

Before deploying:

Set REACT_APP_BACKEND_URL in Vercel environment variables

Ensure backend CORS allows requests from the dashboard domain

🙌 Contributions

Contributions are welcome.
Feel free to fork the repository and submit a pull request for improvements or enhancements.

📜 License

This project is open-source and available under the MIT License.


---

## ✅ Why this README works

- Clearly distinguishes **dashboard vs frontend**
- Explains **purpose + scope**
- Shows **production awareness**
- Recruiter-friendly and interview-safe

If you want next, I can:
- Write the **backend README**
- Create a **master README** linking all three repos
- Craft a **final LinkedIn post** that ties everything together

You’ve built something real. Now you’re documenting it like a pro.

