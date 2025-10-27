🔗 Habitraker: Collaborative Habit Tracker

Habitraker is a full-featured, real-time web application designed for tracking daily habits, building streaks, and running collaborative group challenges. It helps you stay accountable to your personal goals and compete alongside your friends. Built with plain HTML, Tailwind CSS, and powered by Google Firestore for persistent, real-time data storage.

🌟 Live Demo

See Habitraker Live Here (Insert Your Netlify URL)

✨ Core Features

Real-Time Tracking: Track and update daily activities instantly. All data saves permanently to Google Firestore.

Dynamic Habit Customization: Define and manage your own habits (checkbox, duration, quantity) with custom targets and unique colors.

Day Streak Calculation: Automatically tracks and displays your current longest streak of perfect days (10/10 score).

Group & Collaboration: Easily create a new group or join a group using a shared ID to collaborate with friends.

Challenge System: Create Solo or Group Challenges against defined metrics (e.g., "Complete 50 total hours of learning in 2 weeks").

Interactive Calendar: Select and view the historical progress and score of any past day.

Responsive Design: Optimized for seamless use across all devices (mobile, tablet, desktop).

🛠️ Technology Stack

Frontend: HTML5

Styling/Layout: Tailwind CSS (via CDN)

Logic: Vanilla JavaScript (ES6+)

Database: Google Firestore (Real-Time NoSQL Database)

Authentication: Firebase Auth (Anonymous/Custom Token)

🚀 Getting Started (Deployment)

This application requires a live web environment to securely handle user authentication and database connections. Opening the file locally (via file:///) will cause connection errors.

Quick Start

Clone this repository.

Open the index.html file in your preferred browser. (Note: Data saving will not work until deployed to a server)

Deploying to Netlify (Recommended)

Save the latest code as a single file named index.html.

Go to Netlify and log in.

In your dashboard, use the drag-and-drop feature to upload your index.html file.

Once deployed, change the site name (e.g., to habitraker-app) under Site settings to get a clean URL (e.g., https://habitraker-app.netlify.app).

🤝 Contribution

Future enhancements include displaying group members' progress, a visual challenge leaderboard, and setting customized color themes.

Feel free to open issues to report bugs or suggest new features, or submit pull requests with improvements!
