# Real-Time Chat Application

A simple real-time chat application built with React, Vite, and Firebase. This application allows users to communicate in real-time, update their profiles, and manage conversations seamlessly.


## 🌟 Features

- *Real-time messaging*
- *User authentication* (Login/Signup)
- *Profile customization*
- *Password reset functionality*
- *Message status indicators*
- *Online/Offline status*
- *Profile picture upload*
- *Responsive design*

## 🚀 Tech Stack

- React.js (Frontend UI)
- HTML5 & CSS3 (Frontend)
- Vite (build tool)
- Firebase (Authentication, Firestore, Storage)


## 📁 Project Structure

```
src/
├── assets/           # Images and static assets
├── components/       # Reusable components
│   ├── ChatBox/      # Chat interface component
│   ├── LeftSidebar/  # Navigation sidebar
│   └── RightSidebar/ # User info sidebar
├── config/           # Firebase configuration
├── context/          # React context for state management
├── lib/              # Utility functions
└── pages/            # Main application pages
    ├── Chat/         # Main chat interface
    ├── Login/        # Authentication page
    └── ProfileUpdate/# Profile settings page
```

## 🛠 Setup and Installation

1. Clone the repository:
bash
git clone https://github.com/yourusername/chatapp.git
cd chatapp


2. Install dependencies:
bash
npm install


3. Create a .env file in the root directory and add your Firebase configuration:
env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_measurement_id


4. Start the development server:
bash
npm run dev



## 🔑 Firebase Setup

1. Create a new Firebase project
2. Enable Authentication (Email/Password)
3. Create a Firestore database
4. Enable Storage for file uploads
5. Add your Firebase configuration to the .env file

## 💡 Usage

1. Create an account or log in
2. Update your profile (optional)
3. Start chatting with other users
4. Upload images in chats
5. View online/offline status of users
6. Update profile settings as needed
