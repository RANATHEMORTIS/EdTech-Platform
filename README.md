# 📚 StudyNotion – The Future of Online Learning 🚀  

[![StudyNotion](https://img.shields.io/badge/Live%20Project-View%20Now-brightgreen?style=for-the-badge)](https://studynotion-edtech-project.vercel.app/)  
A **Next-Generation EdTech Platform** that brings students and instructors together for an interactive learning experience.  

> **Empowering education with technology!** 🎓  

---

## 🌟 **Live Preview**  
🔗 **Live Website:** 👉 [StudyNotion](https://studynotion-edtech-project.vercel.app/)  

---

## 🎯 **Project Overview**  

### ✨ **What is StudyNotion?**  
StudyNotion is a feature-rich online education platform built using the **MERN stack**. It allows users to:  
✅ Enroll in courses  
✅ Track learning progress  
✅ Interact with instructors  
✅ Manage payments seamlessly  

📚 **Tech Stack Used:**  
- **Frontend:** React.js, Redux, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT-based authentication  
- **Payment Gateway:** Razorpay  
- **Cloud Storage:** Cloudinary  
- **Hosting:** Vercel (Frontend), Render (Backend)  

---

## 🚀 **Features**  

### 🔹 **User Roles & Authentication**  
✔️ Student, Instructor, and Admin roles  
✔️ Secure login/signup with JWT  
✔️ Forgot password & email verification  

### 🔹 **Course Management**  
✔️ Create, update, delete courses  
✔️ Add modules & lessons with videos  
✔️ Track course progress  

### 🔹 **Payment & Subscription**  
✔️ Secure payments via Razorpay  
✔️ Dynamic course pricing  
✔️ Purchase history & invoices  

### 🔹 **Interactive Learning**  
✔️ Discussion forums for Q&A  
✔️ Personalized dashboards  
✔️ Notifications for updates  

### 🔹 **Admin Dashboard**  
✔️ Manage users, courses, & revenue  
✔️ Track sales & user activity  
✔️ Secure data handling  

---


---

## 🔑 **Environment Variables (`.env`)**  

Create a **`.env`** file in the **root directory** and add the following:  

```sh
# 🚀 Server Environment Variables
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret

# 🚀 Client Environment Variables
REACT_APP_API_BASE_URL=http://localhost:5000/api
REACT_APP_RAZORPAY_KEY=your_razorpay_key_id
---------------------
🚀 Installation Guide
1️⃣ Clone the Repository
.....
git clone https://github.com/your-username/StudyNotion.git
cd StudyNotion
--------------
2️⃣ Install Dependencies
Frontend
sh
Copy
Edit
.......
cd client
npm install
-------------
Backend
sh
Copy
Edit
.........
cd server
npm install
-------------
🚀 Deployment Guide
✅ Deploying Frontend on Vercel
Install Vercel CLI
sh
Copy
Edit
npm install -g vercel
Deploy
sh
Copy
Edit
vercel --prod
✅ Deploying Backend on Render
Push code to GitHub
Go to Render Dashboard → Create a new Web Service
Connect GitHub Repo & Deploy 🚀
--------------------------------------------------
🤝 Contributing
We ❤️ contributions! Follow these steps to contribute:

Fork the repository
Create a new branch (git checkout -b feature-branch)
Make changes and commit (git commit -m "Added new feature")
Push to GitHub (git push origin feature-branch)
Create a Pull Request (PR)
Your contributions make StudyNotion better! 🌟
