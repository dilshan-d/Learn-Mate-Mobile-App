LEARNMATE (LEARNING MANAGEMENT SYSTEM)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎯 PROJECT OVERVIEW:
A comprehensive Learning Management System designed specifically for educational
institutions. Provides complete academic management including exam scheduling,
timetable management, marks tracking, and a sophisticated communication module
with automated notifications.

📌 KEY FEATURES:
• User Management: Multi-role system (Admin, Teacher, Student)
• Exam Management: Create, schedule, and manage exams with date/time
• Timetable Scheduling: Dynamic class and exam scheduling system
• Marks Management: Release and track student performance
• Real-Time Communication: Messaging and announcements system
• Automated Notifications:
  - New exam notifications when posted
  - Timetable update alerts for classes
  - Marks release notifications for students
• Notification History: Track all communications
• Role-Based Visibility: Smart filtering based on user roles
• File Attachments: Upload documents with notifications

💼 BUSINESS VALUE:
Automates academic processes, improves communication between teachers and students,
ensures timely notifications for important academic events, and streamlines
administration for educational institutions.

🛠️ Tech Stack

Backend: Node.js, Express.js, MongoDB with Mongoose
Frontend/Mobile: React/React Native, Vite, Tailwind CSS
Database: MongoDB with advanced data models
Communication: WebSocket support, real-time updates
Security: JWT tokens, Bcrypt hashing

Mobile/Frontend
- **Framework**: React Native / React
- **UI Framework**: Modern responsive components
- **State Management**: Context API / Redux
- **Navigation**: React Navigation

Database
- **Primary**: MongoDB
- **Models**: Notification, User, Exam, Timetable, Marks, SchoolClass, Subject

Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas cluster)
- npm or yarn
- Mobile development tools (for mobile app)

Installation & Setup

Backend Setup
cd LearnMate-WMT-main/backend
npm install

Create .env file
cat > .env << EOF
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
NODE_ENV=development
EOF

npm start
\\\

Mobile App Setup

cd LearnMate-WMT-main/mobile
npm install or npm install

For development
npm run dev

