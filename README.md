# Image-Upload-Gallery-with-Approval
# 📸 Image Upload & Gallery with Approval 

## 📌 Project Overview  
**Hackathon:** Web Wizards Hackathon 2025  
**Project Title:** Image Upload & Gallery with Approval Workflow  
**Team Name:** FULL-STACK FORCE  

### 👨‍💻 Team Members  
- Member 1-Parth Shah – Role (Frontend Developer)  
- Member 2 –Het Patel- Role (Backend Developer)  
- Member 3 –Yansh patel-Role (Designer/Documentation)
- Member 4- Sneh Patel -Role (Database Developer)
- 

---

## 🚀 Problem Statement  
Universities often organize events and competitions where students want to upload and showcase their photos. However, without moderation, inappropriate or irrelevant content may appear.  

---

## 💡 Solution  
We built a **web application** that ensures students can upload their images, while admins approve them before they are displayed in a **public gallery**.  

- **Users (Students):** Upload image with name, email, and caption.  
- **Admin:** Secure login, review pending uploads, approve/reject images.  
- **Gallery:** Displays only approved images (with thumbnail, caption, and uploader name).  

---

## 🔑 Features  

### 👤 User Features  
✔ Upload image with caption, name, email  
✔ View gallery of approved images  
✔ Simple and responsive UI  

### 🔐 Admin Features  
✔ Secure login system  
✔ Approve or reject uploaded images  
✔ Manage public gallery  

---

## 🛠 Tech Stack  

- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Token (JWT)  
- **Storage:** Local server / Cloud storage (if used)  
- **Deployment:** [Vercel/Netlify for frontend, Render/Heroku for backend]  

---

## 🏗 System Architecture  

![System Architecture](./docs/architecture.png)  

```plaintext
 Student (User) ---> Frontend (React + Tailwind) ---> Backend (Express API) ---> MongoDB
                                                             │
                                                             └---> Admin Panel ---> Approval Workflow ---> Gallery
##SETUP Instructions:
Installation & Setup
🔹 Clone Repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

🔹 Frontend Setup
cd frontend
npm install
npm start

🔹 Backend Setup
cd backend
npm install
npm run dev
