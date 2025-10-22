# 🍽️ DAAWAT – Food Waste Management System

DAAWAT is a **web-based food waste management system** designed to promote community-driven food sharing.  
It enables users to **host** leftover food events and allows others to **attend** them based on **real-time location**.  
The platform aims to minimize food waste and ensure surplus food reaches those who need it most.

---

## 🚀 Features

- 👤 **User Authentication** — Secure login and signup using Firebase Authentication.  
- 📍 **Location-Based Services** — Integration with Google Maps API to locate nearby food-sharing events.  
- 🍱 **Host Daawat** — Users can post leftover food details (type, quantity, expiry time, location, etc.).  
- 🍽️ **Attend Daawat** — Users can discover and attend nearby hosted food events.  
- ⭐ **Feedback System** — Attendees can rate and review hosts after food collection.  
- 🕒 **Auto Expiry** — Food listings automatically expire after a specified time.  
- 📱 **Responsive UI** — Designed with a mobile-first approach for accessibility on all devices.  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Firebase (Authentication & Realtime Database) |
| **Database** | Firebase Firestore |
| **Location Services** | Google Maps API, Geolocation API |
| **Version Control** | Git, GitHub |
| **Hosting** | Firebase Hosting |

---

## 🛠️ Installation & Setup

Follow the steps below to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/daawat.git
cd daawat
```
2. Create Firebase Project  
Go to Firebase Console  
Create a new project  
Enable Firebase Authentication and Firestore Database  
Copy your Firebase config credentials  
  
3. Add Firebase Config  
In your project folder, create a new file named firebaseConfig.js and add:  
```
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};

export default firebaseConfig;
```
4. Install Dependencies (optional, if using a build tool)
```
npm install
```
5. Run the Project  
Simply open index.html in your browser  
or deploy using Firebase:  
```
firebase deploy
```
## 📸 Screenshots  

## 🌱 Future Enhancements  
🔔 Real-time notifications for new nearby daawats  
🤝 NGO & volunteer organization integration  
💬 Chat or messaging between host and attendees  
📊 Food waste analytics dashboard  
🌐 Multilingual support for wider accessibility  

	
## ✍️ About Developer  
<p align="center">
  <img src="https://github.com/user-attachments/assets/a615929b-6615-46fc-9046-19a7ed74d5c0" alt="Developer Image" width="200"/>
</p>

<h3 align="center">Pradeep Singh</h3>

<p align="center">
  <a href="https://github.com/pradeep-r04">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/pradeep-singh4/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>



## 🌍 “DAAWAT bridges communities through technology — turning surplus into smiles.”
