# DriveMate - Driving School Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Team Size](https://img.shields.io/badge/Team-6%20Members-blue.svg)](https://github.com/lesego-lebese/drivemateproject)

A full-stack driving school management system built with React + TypeScript (frontend) and Node.js + Express (backend), using SQLite database via Prisma ORM.

## 🚀 Project Overview

DriveMate helps driving schools manage students, instructors, bookings, payments, progress tracking, messaging, reminders, and admin reporting in a single local system.

### Key Features
- **Student Management**: Lesson booking, progress tracking, quiz practice
- **Instructor Tools**: Schedule management, student progress review, availability slots
- **Admin Dashboard**: User management, analytics, payment tracking, system oversight
- **Smart Features**: Automated reminders, scheduling recommendations, progress analytics

## 👥 Team Collaboration

This project is developed by a 6-member team with equal contribution:

- **Member 1 (Lesego Lebese)**: Backend API Core & Authentication System
- **Member 2**: Database Schema & Data Management  
- **Member 3**: Frontend Student Features
- **Member 4**: Frontend Instructor Features
- **Member 5**: Frontend Admin Features
- **Member 6**: Shared Components & Utilities

📖 **See [TEAM_COLLABORATION.md](TEAM_COLLABORATION.md) for detailed team structure and responsibilities**

## 🛠️ Tech Stack

### Frontend
- React 18 + TypeScript
- React Router DOM
- Tailwind CSS
- Axios for API calls
- Recharts for analytics
- Lucide React icons

### Backend
- Node.js + Express.js
- Prisma ORM
- SQLite Database
- JWT Authentication
- bcryptjs for password hashing
- CORS enabled

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Git

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/lesego-lebese/drivemateproject.git
cd drivemateproject
```

### 2. Install Dependencies
```bash
# Root dependencies
npm install

# Backend dependencies
cd backend
npm install

# Frontend dependencies  
cd ../frontend
npm install
```

### 3. Database Setup
```bash
cd backend
npx prisma db push
node prisma/seed.js
```

### 4. Start the Application
```bash
# Terminal 1 - Backend (port 5000)
cd backend
npm run dev

# Terminal 2 - Frontend (port 3000)
cd frontend
npm start
```

### 5. Access the Application
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5000

## 🔐 Demo Credentials

### Admin
- Email: lesego@drivemate.co.za
- Password: Admin@123

### Instructor
- Email: sipho.khumalo@drivemate.co.za
- Password: Instructor@123

### Student
- Email: thando.zungu@example.co.za
- Password: Student@123

## 📁 Project Structure

```
drivemateproject/
├── backend/
│   ├── prisma/
│   │   ├── schema.prisma      # Database schema
│   │   └── seed.js            # Sample data
│   ├── server.js              # Express server
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── pages/             # Page components
│   │   ├── components/        # Reusable components
│   │   ├── context/           # React contexts
│   │   └── lib/               # Utilities & API
│   └── package.json
├── package.json               # Root scripts
├── README.md                  # This file
└── TEAM_COLLABORATION.md      # Team guide
```

## 🔄 Development Workflow

### For Team Members
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/memberX-description`
3. Make your changes following assigned responsibilities
4. Test thoroughly
5. Commit with clear messages: `[Member X] feat: description`
6. Push and create a pull request
7. Request review from relevant team members

### Branch Naming
- `feature/memberX-description` - New features
- `bugfix/memberX-description` - Bug fixes
- `hotfix/memberX-description` - Urgent fixes

## 🧪 Testing

```bash
# Frontend tests
cd frontend
npm test

# Backend tests (when implemented)
cd backend
npm test
```

## 📝 Available Scripts

### Root
```bash
npm run setup      # Install all dependencies
npm run dev        # Start both frontend and backend
npm run db:setup   # Setup database
```

### Backend
```bash
npm start          # Start production server
npm run dev        # Start development server with hot reload
npm run db:push    # Push Prisma schema to database
npm run db:studio  # Open Prisma Studio
npm run db:seed    Seed database with sample data
```

### Frontend
```bash
npm start          # Start development server
npm run build      # Build for production
npm test           # Run tests
```

## 🤝 Contributing

This is a collaborative project. Please:
1. Read [TEAM_COLLABORATION.md](TEAM_COLLABORATION.md) for team guidelines
2. Follow the assigned responsibilities for your role
3. Use proper branch naming and commit messages
4. Test your changes before creating PRs
5. Communicate with the team for major changes

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Built for local driving school management
- Team collaboration project with equal contribution
- Demo purposes and educational use

---

**Repository Owner**: Lesego Lebese  
**Team Size**: 6 Members  
**Last Updated**: September 2024