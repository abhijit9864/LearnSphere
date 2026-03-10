# API Structure

## Authentication

POST /api/auth/register
POST /api/auth/login
POST /api/auth/reset-password

---

## Organizations

POST /api/organizations
GET /api/organizations

---

## Users

POST /api/users
GET /api/users
PUT /api/users/:id
DELETE /api/users/:id

---

## Courses

POST /api/courses
GET /api/courses
GET /api/courses/:id

---

## Lessons

POST /api/lessons
GET /api/lessons/:courseId

---

## Quizzes

POST /api/quizzes
GET /api/quizzes/:courseId
