# API DESIGN

## Authentication

POST /api/v1/auth/register

POST /api/v1/auth/login

GET /api/v1/auth/me

---

## Profile

GET /api/v1/profile

PUT /api/v1/profile

---

## Resume

POST /api/v1/resume/upload

GET /api/v1/resume

DELETE /api/v1/resume/{id}

---

## Roadmaps

GET /api/v1/roadmaps

GET /api/v1/roadmaps/{id}

---

## Jobs

GET /api/v1/jobs

GET /api/v1/jobs/{id}

POST /api/v1/jobs/apply

---

## AI Assistant

POST /api/v1/ai/chat

POST /api/v1/ai/resume-review