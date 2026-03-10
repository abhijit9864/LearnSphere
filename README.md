# LearnSphere - Learning Management SaaS Platform

LearnSphere is a **multi-tenant Learning Management System (LMS)** built as a **SaaS platform** that enables organizations to create, manage, and deliver online training programs.

The platform allows organizations to manage employee learning through course management, assessments, analytics, and user administration.

---

# 🚀 Project Overview

LearnSphere provides a centralized system for companies to manage their training and development programs.

Each organization operates within its own isolated environment, ensuring secure data separation through a **multi-tenant architecture**.

Key capabilities include:

* Course creation and management
* Instructor-led training
* Student learning dashboards
* Assessment and grading system
* Learning analytics and reporting
* Notification system

---

# 🧠 Core Features

## Multi-Tenant Architecture

* Organization-based environments
* Custom branding support
* Storage quota management
* Subscription plan support

## User Management

Role-based access control with four primary roles:

* System Administrator
* Organization Administrator
* Instructor
* Student

Features include:

* Secure authentication
* Password reset
* Session management
* Two-factor authentication (future)

---

## Course Management

Organizations can create structured courses including:

* Modules
* Lessons
* Videos
* Documents
* Quizzes

Supported content formats:

* Video lectures
* PDF files
* Presentations
* Audio files
* HTML content
* Interactive quizzes

---

## Assessment System

LearnSphere includes a built-in evaluation system.

Features:

* Quiz creation
* Question banks
* Automated grading
* Manual assignment grading
* Time-limited assessments
* Attempt limits

---

## Analytics & Reporting

The platform provides detailed insights including:

* Course completion rates
* Student engagement metrics
* Assessment performance
* Resource utilization

Reports can be exported and filtered.

---

# 🏗 System Architecture

LearnSphere follows a scalable SaaS architecture.

Client (React Frontend)
↓
Node.js API Server
↓
Application Services
↓
MySQL Database
↓
Cloud Storage (Video & Files)

Each organization is identified using a **tenant_id** to ensure data isolation.

---

# 📂 Project Structure

```
learnsphere-lms
│
├── backend
├── frontend
│
├── docs
│   ├── SRS.md
│   ├── TECH_STACK.md
│   ├── ARCHITECTURE.md
│   ├── DATABASE_DESIGN.md
│   ├── API_STRUCTURE.md
│   └── DEVELOPMENT_ROADMAP.md
│
└── README.md
```

---

# 👨‍💻 Author

Abhijit Pradhan
Full Stack Developer (MERN Stack)

Experience:

* LMS Platform Development
* Document Management Systems
* Scalable Backend APIs
* Secure Authentication Systems
