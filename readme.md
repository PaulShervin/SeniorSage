# 🚀 SeniorSage – AI Powered College Guidance & Mentorship Platform

SeniorSage is a centralized mentorship platform that connects school students (Juniors) with verified college seniors using AI-powered recommendations, smart search, real-time messaging, and structured forums.

---

# 📌 Table of Contents

- Overview
- Features
- Feature Details
- System Workflow
- Tech Stack
- API Endpoints
- Security
- Installation
- Future Enhancements

---

# 📖 Overview

SeniorSage solves the problem of fragmented and unreliable college guidance by providing:

- Verified senior mentorship
- AI-based recommendations
- Real-time messaging
- College-specific forums
- Secure and scalable system

---

# ✨ Features

✔ Authentication System
✔ Role-Based Access Control
✔ Profile Management
✔ Smart Senior Search
✔ AI-Powered Recommendation
✔ Real-Time Chat System
✔ Forum System
✔ College Search System
✔ Secure Backend APIs


---

# 🧩 Feature Details

---

## 🔐 1. Authentication System

### Description
Secure login and registration using JWT authentication.

### Features

```
• User Registration
• User Login
• JWT Token Generation
• Secure Authentication
```

### API

```
POST /api/auth/login
POST /api/users/register
```

---

## 👤 2. Role-Based Access Control

### Roles

```
JUNIOR:
• Search seniors
• View profiles
• Chat with seniors
• Comment on posts

SENIOR:
• Create posts
• Reply to juniors
• Manage profile
• Provide mentorship
```

---

## 🧑‍💼 3. Profile Management

### Features

```
• Create profile
• Update profile
• Upload profile image
• View profile
```

### API

```
GET /api/users/profile
PUT /api/users/profile
POST /api/users/profile/image
```

---

## 🔍 4. Smart Senior Search

### Features

```
• Search by college
• Search by branch
• Search by course
• Search by location
```

### Purpose

```
Helps juniors find relevant seniors easily.
```

---

## 🤖 5. AI-Powered Recommendation System

### Features

```
• AI analyzes junior preferences
• Recommends best matching seniors
• Uses Gemini AI
• Vector search support (planned)
```

---

## 💬 6. Real-Time Chat System

### Features

```
• Send message
• Receive message
• Chat history
• Real-time communication
```

### API

```
POST /api/chat/send
GET /api/chat/history/{userId}
```

---

## 🧵 7. Forum System (Core Feature)

### Senior Permissions

```
• Create posts
• Share experiences
• Provide guidance
```

### Junior Permissions

```
• View posts
• Comment on posts
• Like posts
```

### API

```
POST /api/forums
POST /api/forums/{forumId}/posts
POST /api/forums/posts/{postId}/comments
```

---

## 🏫 8. College Search System

### Features

```
• Search colleges
• Filter by name
• Filter by city
• Filter by course
```

### API

```
GET /api/colleges/search
```

---

# 🔄 System Workflow

```
1. User registers
2. User selects role (Junior / Senior)
3. User creates profile
4. Junior searches seniors
5. AI recommends seniors
6. Junior views profile
7. Junior starts chat
8. Senior responds
9. Users participate in forums
```

---

# 🛠 Tech Stack

## Frontend
```
React.js
HTML
CSS
JavaScript
```

## Backend
```
Spring Boot
Java
REST APIs
```

## Database
```
MySQL
```

## AI
```
Gemini AI
Vector Search (planned)
```

## Security
```
Spring Security
JWT Authentication
```

## Communication
```
WebSocket
```

---

# 🔗 API Endpoints

## Authentication
```
POST /api/auth/login
POST /api/users/register
```

## User
```
GET /api/users/profile
PUT /api/users/profile
POST /api/users/profile/image
```

## Chat
```
POST /api/chat/send
GET /api/chat/history/{userId}
```

## Forum
```
POST /api/forums
POST /api/forums/{forumId}/posts
POST /api/forums/posts/{postId}/comments
```

## Colleges
```
GET /api/colleges/search
```

---

# 🔒 Security Features

```
• JWT Authentication
• Role-Based Authorization
• Secure APIs
• Protected Endpoints
• Encrypted Data
```

---

# ⚙ Installation

## Backend

```bash
git clone https://github.com/your-repo/seniorsage.git
cd backend
mvn spring-boot:run
Frontend
cd frontend
npm install
npm start
🚀 Future Enhancements
• AI Chatbot Mentor
• Internship mentorship
• Alumni mentorship
• Mobile Application
• Advanced AI Matching
👨‍💻 Author
Team DevMatrix
SeniorSage Project
