# SeniorSage – AI Powered College Guidance & Mentorship Platform

SeniorSage is a centralized mentorship platform that connects school students (juniors) with verified college seniors using AI-powered recommendations, smart search, real-time messaging, and structured forums.

## Table of Contents

- Overview
- Features
- Feature Details
- System Workflow
- Tech Stack
- API Endpoints
- Security
- Installation
- Future Enhancements
- Author

## Overview

SeniorSage solves the problem of fragmented and unreliable college guidance by providing:

- Verified senior mentorship
- AI-based recommendations
- Real-time messaging
- College-specific forums
- Secure and scalable system

## Features

- Authentication system
- Role-based access control
- Profile management
- Smart senior search
- AI-powered recommendations
- Real-time chat system
- Forum system
- College search system
- Secure backend APIs

## Feature Details

### 1) Authentication System

**Description:** Secure login and registration using JWT authentication.

**Features:**
- User registration
- User login
- JWT token generation
- Secure authentication

**API:**
- `POST /api/auth/login`
- `POST /api/users/register`

### 2) Role-Based Access Control

**Roles:**

**JUNIOR**
- Search seniors
- View profiles
- Chat with seniors
- Comment on posts

**SENIOR**
- Create posts
- Reply to juniors
- Manage profile
- Provide mentorship

### 3) Profile Management

**Features:**
- Create profile
- Update profile
- Upload profile image
- View profile

**API:**
- `GET /api/users/profile`
- `PUT /api/users/profile`
- `POST /api/users/profile/image`

### 4) Smart Senior Search

**Features:**
- Search by college
- Search by branch
- Search by course
- Search by location

**Purpose:** Helps juniors find relevant seniors easily.

### 5) AI-Powered Recommendation System

**Features:**
- AI analyzes junior preferences
- Recommends best matching seniors
- Uses Gemini AI
- Vector search support (planned)

### 6) Real-Time Chat System

**Features:**
- Send message
- Receive message
- Chat history
- Real-time communication

**API:**
- `POST /api/chat/send`
- `GET /api/chat/history/{userId}`

### 7) Forum System (Core Feature)

**Senior permissions:**
- Create posts
- Share experiences
- Provide guidance

**Junior permissions:**
- View posts
- Comment on posts
- Like posts

**API:**
- `POST /api/forums`
- `POST /api/forums/{forumId}/posts`
- `POST /api/forums/posts/{postId}/comments`

### 8) College Search System

**Features:**
- Search colleges
- Filter by name
- Filter by city
- Filter by course

**API:**
- `GET /api/colleges/search`

## System Workflow

1. User registers
2. User selects role (Junior or Senior)
3. User creates profile
4. Junior searches seniors
5. AI recommends seniors
6. Junior views profile
7. Junior starts chat
8. Senior responds
9. Users participate in forums

## Tech Stack

**Frontend**
- React.js
- HTML
- CSS
- JavaScript

**Backend**
- Spring Boot
- Java
- REST APIs

**Database**
- MySQL

**AI**
- Gemini AI
- Vector search (planned)

**Security**
- Spring Security
- JWT authentication

**Communication**
- WebSocket

## API Endpoints

**Authentication**
- `POST /api/auth/login`
- `POST /api/users/register`

**User**
- `GET /api/users/profile`
- `PUT /api/users/profile`
- `POST /api/users/profile/image`

**Chat**
- `POST /api/chat/send`
- `GET /api/chat/history/{userId}`

**Forum**
- `POST /api/forums`
- `POST /api/forums/{forumId}/posts`
- `POST /api/forums/posts/{postId}/comments`

**Colleges**
- `GET /api/colleges/search`

## Security

- JWT authentication
- Role-based authorization
- Secure APIs
- Protected endpoints
- Encrypted data

## Installation

### Backend

```bash
git clone https://github.com/your-repo/seniorsage.git
cd backend
mvn spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm start
```

## Future Enhancements

- AI chatbot mentor
- Internship mentorship
- Alumni mentorship
- Mobile application
- Advanced AI matching

## Author

Team DevMatrix
SeniorSage Project
