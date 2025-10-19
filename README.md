📘 ProjScope – Project Idea Analyzer (MITS College)
🔍 Overview

ProjScope is a web-based platform designed for final-year students to check whether their project idea already exists or has been implemented in hackathons, GitHub repositories, or academic research.
It helps students identify unique and innovative project ideas by analyzing and comparing them with existing ones.

🎯 Goal

To assist students in avoiding repetitive or copied projects and inspire original, creative, and technically feasible ideas for their final-year submissions or hackathons.

🧩 Features

✅ Login and Register using Roll Number, Batch Year, and Department (stored in browser LocalStorage)
✅ Dashboard to enter and analyze project ideas
✅ Checks similarity with existing static database of common projects
✅ Displays detailed analysis report:

Status (Exists / New)

Previous Implementations

Drawbacks & Improvement areas

Suggestions for Uniqueness

Recommended Tech Stack

Project Roadmap
✅ Works completely offline using LocalStorage (no backend required)
✅ Fully responsive UI with college banner (MITS logo) on every page

🏗️ Folder Structure
ProjScope/
│
├── index.html          # Login / Register page
├── dashboard.html      # Main project idea analyzer
├── history.html        # History of analyzed ideas (optional)
├── about.html          # About page
├── contact.html        # Contact info
│
├── css/
│   └── styles.css      # Common styles for all pages
│
├── js/
│   ├── auth.js         # Handles login/register logic
│   ├── dashboard.js    # Analyzes project ideas
│   └── history.js      # Displays saved project analyses
│
├── images/
│   └── mitslogo.png    # MITS College banner logo
│
└── README.md           # Documentation file

⚙️ How It Works

1️⃣ Student logs in using Roll Number and Batch Year.
2️⃣ Enters project idea on the dashboard.
3️⃣ The system compares the text with static existing project titles.
4️⃣ Displays whether the project already exists or is new.
5️⃣ Gives detailed suggestions and a roadmap for development.

💡 Example Workflow

Input:

“AI-based Attendance System using Face Recognition”

Output:

Status: Exists
Previous Implementations: Face Recognition Attendance System (2021 batch)
Drawbacks / Improvements: Accuracy drops under poor lighting; lacks mobile integration
Suggestions for Uniqueness: Add liveness detection & integrate with college ERP
Recommended Tech Stack: Python, OpenCV, Firebase, React.js
Project Roadmap:
  - Collect student dataset
  - Train face recognition model
  - Integrate with login system
  - Add mobile scanning feature

🖥️ Tech Stack

Frontend: HTML, CSS, JavaScript

Database: Browser LocalStorage (for demo)

Deployment: Vercel / GitHub Pages

Optional Future Upgrade: Firebase / FastAPI backend

🚀 Setup & Run

1️⃣ Download or clone this repo
2️⃣ Open the folder ProjScope
3️⃣ Double-click on index.html to run locally
4️⃣ Or deploy it directly on Vercel

🌐 Deployment (Vercel Steps)

Go to Vercel.com

Click “New Project” → Import Folder

Select your folder (with index.html)

Click Deploy

Share your live URL with friends or faculty

🧠 Future Enhancements

Integrate with real-time databases (Firebase / MongoDB)

Add AI text similarity model (like BERT) for idea analysis

Generate project reports automatically (PDF)

Add student leaderboard for innovative ideas

✨ Developed By

Puneeth Kumar (MITS College – CSE-AI, Batch 2024)
“Innovating projects for innovators.”
