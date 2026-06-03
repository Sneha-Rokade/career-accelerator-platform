# DATABASE DESIGN

## USERS

| Column | Type |
|----------|----------|
| id | UUID |
| name | VARCHAR |
| email | VARCHAR |
| password_hash | VARCHAR |
| created_at | TIMESTAMP |

---

## PROFILES

| Column | Type |
|----------|----------|
| id | UUID |
| user_id | UUID |
| bio | TEXT |
| skills | TEXT |
| experience | TEXT |

---

## RESUMES

| Column | Type |
|----------|----------|
| id | UUID |
| user_id | UUID |
| file_url | TEXT |
| uploaded_at | TIMESTAMP |

---

## ROADMAPS

| Column | Type |
|----------|----------|
| id | UUID |
| title | VARCHAR |
| category | VARCHAR |

---

## USER_PROGRESS

| Column | Type |
|----------|----------|
| id | UUID |
| user_id | UUID |
| roadmap_id | UUID |
| completed_percentage | INTEGER |

---

## JOBS

| Column | Type |
|----------|----------|
| id | UUID |
| company_name | VARCHAR |
| title | VARCHAR |
| description | TEXT |

---

## APPLICATIONS

| Column | Type |
|----------|----------|
| id | UUID |
| user_id | UUID |
| job_id | UUID |
| status | VARCHAR |