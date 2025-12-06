Our Private App 💖

A private, interactive web app for sharing music, pictures, chats, mini-games, and love notes. Built with Firebase and Vanilla JS, with a modern, mobile-friendly interface and dark/light mode support.


---

Features

🔐 Login / Sign Up with Firebase Authentication

🎵 Music Page: Play songs, add your own

📸 Gallery: Upload and view images with captions

💬 Live Chat: Real-time chat using Firestore

🎮 Mini Game: Click-button score game

💌 Extra Page: Cute love notes, interactive surprises

🌗 Dark / Light Mode toggle

🚪 Logout button

🖥️ Fully responsive and mobile-friendly



---

Firebase Setup

1. Go to Firebase Console and create a new project.


2. Enable Authentication → Email/Password.


3. Enable Firestore Database.


4. Enable Storage (optional, for images/audio).



Required Firestore Collections

Collection	Fields

users	username (string), email (string), admin (boolean)
songs	name (string), url (string), uploadedBy (string)
pictures	url (string), caption (string), uploadedBy (string)
messages	sender (string), content (string), timestamp (timestamp)


> Admin flag is set manually in Firestore if needed.




---

How to Use

1. Clone or download the repository.


2. Open the HTML file in a browser (or host via Vercel / Netlify).


3. First-time users Sign Up with email, password, and username.


4. Login to access the app: music, gallery, chat, games, and extra page.


5. Upload songs, pictures, or send messages — all synced in real-time.




---

Dark / Light Mode

Toggle the theme using the 🌓 button in the navbar.

Dark mode adds a soft, romantic dark gradient background.



---

Notes

Only logged-in users can see the app content.

“Babe” is used in the love note instead of the real name for privacy.

All media (songs, images) are stored in Firebase Storage.

Real-time updates are powered by Firestore.



---

Deployment

You can host the app as a static website via Vercel or Netlify.

Make sure your Firebase project config in the script matches your own Firebase project.



---

Tech Stack

HTML / CSS / JS

Firebase Authentication, Firestore, Storage

Responsive design + interactive effects
