SkillSphere: Learning Management System

Version: 1.0
Team Name: CodExplorers
Project Type: Web Application
Theme: AI-Powered Learning Solutions
Deployed Link: SkillSphere on Vercel 🚀

GitHub Repository: Source Code

Hackathon: Synapse 2K25 – Mohan Babu University
About the Project

SkillSphere is an advanced, AI-powered Learning Management System (LMS) designed to revolutionize modern education with technology and interactivity.

It provides a seamless learning ecosystem where teachers can manage courses and students can learn, collaborate, and track progress — all within an engaging, visually appealing interface.

Our mission is to enhance education through innovation, merging design, technology, and interactivity to deliver an intelligent and immersive learning experience.
Security Notice

This project uses environment variables to protect sensitive Firebase configurations.
The actual API keys are NOT committed to the repository.

Setting Up Environment Variables

Copy .env.example to .env

cp .env.example .env
Fill in your Firebase configuration values in .env

For Vercel deployment, add these environment variables in your Vercel project settings:

VITE_FIREBASE_API_KEY

VITE_FIREBASE_AUTH_DOMAIN

VITE_FIREBASE_DATABASE_URL

VITE_FIREBASE_PROJECT_ID

VITE_FIREBASE_STORAGE_BUCKET

VITE_FIREBASE_MESSAGING_SENDER_ID

VITE_FIREBASE_APP_ID

VITE_FIREBASE_MEASUREMENT_ID

👥 Team CodExplorers
Name	Year	Department
Desetty Jyotsna	II Year	B.Tech – Artificial Intelligence & Machine Learning
Konduru Keerthi	II Year	B.Tech – Artificial Intelligence & Machine Learning
Nagalakshmi	II Year	B.Tech – Artificial Intelligence & Machine Learning
Navya	II Year	B.Tech – Artificial Intelligence & Machine Learning

“CodExplorers” symbolizes a team of innovators exploring technology to reshape learning for the future.

🚀 Core Features
🎓 For Students

Course Discovery: Explore and enroll in multiple skill-based courses with prerequisites.

Personal Dashboard: View enrolled courses, announcements, and completion progress.

Interactive Learning: Access course videos, PDFs, and submit assignments.

Performance Reports: Generate and download personalized performance PDFs.

Discussion Forums: Collaborate with peers and teachers.

Profile Management: Track stats, achievements, and activity.

Gamification: Celebrate 100% course completion with confetti and badges!

🧑‍🏫 For Teachers

Course Management: Create, edit, and manage multiple courses easily.

Material Uploads: Upload videos, documents, and notes.

Assignments & Grading: Evaluate student submissions with remarks.

Announcements: Notify students about updates and discussions.

Dashboard Overview: Monitor student activity and course analytics.

⚙ Tech Stack
Layer	Technology
Frontend	React (with TypeScript)
Styling	Tailwind CSS (via CDN)
Routing	React Router
Database	Firebase / In-Memory Mock API (Demo Mode)
PDF Reports	jsPDF & jsPDF-AutoTable
Design Tool	Figma (AI-assisted for layout and responsiveness)

Lightweight, scalable, and high-performance — built for real-world LMS deployment.

💡 Key Highlights

⚡ Fully client-side LMS — no server setup required

🌐 All dependencies loaded via CDN (no npm build)

🎨 Neo-futuristic dark theme with glassmorphism

📊 Automated performance report generation

🔐 Firebase-ready structure for scalability

💬 Real-time discussions and community learning

🧰 How to Run Locally
Option 1: Using Python HTTP Server

Open the project folder in your terminal.

Run:

python -m http.server


Open your browser and go to:

http://localhost:8000


The app will load instantly!

Option 2: Using VS Code Live Server

Install the Live Server extension in VS Code.

Right-click index.html → Select “Open with Live Server”.

The app will open automatically in your browser.

⚠ Note: The app currently uses a mock API, so data will reset on refresh.

🏁 Future Scope

🔐 Firebase Authentication & Firestore Database Integration

🤖 AI-Based Personalized Course Recommendations

💬 Real-Time Chat & Smart Notifications

🧠 Data-Driven Learning Analytics Dashboard

☁ Cloud Deployment on Firebase / Vercel Pro

🎨 UI & UX Design

Following a neo-futuristic design language — clean, modern, and interactive:

Glassmorphism with elegant gradients

Smooth transitions and responsive layouts

Consistent typography and spacing

Dark mode by default for an immersive feel

Designed using Figma + AI Design Plugin

💬 Team Statement

“Education isn’t just about knowledge — it’s about exploration and growth.
Through SkillSphere, we aim to make learning more intelligent, collaborative, and futuristic.”
