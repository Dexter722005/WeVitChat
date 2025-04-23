# WeVitChat - Real-Time Secure Chat Application

WeVitChat is a real-time chat application built with HTML, JavaScript, and Firebase, designed to enable secure, seamless communication between users. The app supports direct messaging, group chats, status indicators, auto-deleting messages, and includes an integrated cybersecurity assistant and breach-checking tool.

## 🚀 Features

- 🔐 **User Authentication**
  - Login via email or username
  - Secure Firebase Authentication

- 💬 **Messaging System**
  - Real-time private and group messaging
  - Message auto-deletion (1 min to 1 day)
  - Online/offline user status display

- 🧠 **AI Cybersecurity Assistant**
  - Provides cybersecurity tips and news
  - Helps users stay informed and secure

- 🕵️ **Breach Directory Integration**
  - Checks if an email address has been exposed in known data breaches
  - Uses a public API for real-time lookup

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Firebase (Auth + Firestore)
- **Libraries:** Firebase JS SDK
- **APIs:**
  - BreachDirectory API
  - UI Avatars API for profile images

## 📁 File Structure

/project-root │ ├── chat.html # Main chat interface ├── index.html # Login page ├── signup.html # Signup page └── README.md # Project documentation



## 📝 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/wevitchat.git
   cd wevitchat
Firebase Configuration

Create a Firebase project at firebase.google.com

Enable Authentication and Firestore Database

Replace the firebaseConfig object in all HTML files with your project credentials

Run the app

Open index.html in your browser

Create an account and start chatting!

✅ Usage Tips
Try messaging with yourself or another registered user.

Use the Cybersecurity Assistant contact for quick security advice.

Use the Breach Directory contact to check if your email has been exposed.

⚠️ Disclaimer
This is an educational project meant for learning purposes. Do not use real credentials or sensitive data.

📌 Future Improvements
Push notifications

Mobile-friendly layout

End-to-end encryption

Dark mode

👨‍💻 Author
Shreshth Panda
Krishnam Awasthi
Arnav Verma
