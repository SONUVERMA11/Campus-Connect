# Campus-Connect
DTU Connect
A centralized digital hub designed to streamline communication and consolidate essential resources for students, faculty, and administration at Delhi Technological University.

✨ Vision
DTU Connect aims to be the single source of truth for campus life. It transforms the chaotic flow of information from various sources into an organized, accessible, and engaging real-time experience. This project is built as a scalable, single-file web application using modern web technologies.

🚀 Key Features
This application is packed with features to keep the entire campus community informed and connected:

📢 Announcements Hub: A dynamic, filterable feed for all official notices. Admins can post updates with text and file attachments (PDFs, images).

📅 Events Calendar: A clean, chronological list of all upcoming campus events, from workshops and fests to academic deadlines.

📚 Student Resources: A centralized repository for academic materials. Admins can upload syllabi, notes, and previous year papers, or link to external resources.

💬 Community Chat: Real-time, topic-based chat channels where students can interact. Features include media sharing and emoji reactions.

🔐 Secure Authentication: A complete user authentication system with dedicated pages for login and sign-up.

🎛️ Powerful Admin Panel: A comprehensive dashboard for administrators to manage all aspects of the application:

Full CRUD (Create, Read, Update, Delete) operations for Notices, Events, and Resources.

User role management to grant specific permissions.

Dynamic category management for notices and resources.

Community channel management.

🎨 Modern UI/UX:

A clean, responsive, and modern design built with Tailwind CSS.

Light and Dark mode support.

Interactive elements and smooth animations for a great user experience.

💻 Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ES6 Modules)

Backend & Database: Google Firebase

Firestore: Real-time NoSQL database for all application data.

Firebase Authentication: For user sign-up, login, and session management.

Firebase Storage: For handling all file uploads (images, PDFs, documents).

🛠️ Setup & Deployment
This project is a single-file web application that is incredibly easy to deploy.

Firebase Setup: Create a new Firebase project and enable Authentication, Firestore, and Storage.

Configuration: Copy your Firebase project's firebaseConfig object into the index.html file.

Security Rules: Update the Firestore security rules to protect your data.

Deployment: Deploy the index.html file to any static hosting service like Netlify, Vercel, or GitHub Pages.

For a complete walkthrough, please refer to the detailed Deployment Guide.

🔑 Accessing the Admin Panel
The application uses a simple and effective method for initial setup: the first user to sign up automatically becomes the Super Admin.

Simply deploy the application, navigate to the live URL, create an account, and the "Admin Panel" button will appear in the header, giving you full control over the application.
