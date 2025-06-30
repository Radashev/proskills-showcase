# Project Structure – ProSkills Showcase

This folder contains the full **directory structure** of the `proskills` fullstack project:
- 🔧 `ProSkills-BE` — FastAPI backend
- 🌐 `ProSkills-FE` — React frontend
- ⚙️ `terraform` — infrastructure as code

It is shared **without any real code**, intended for documentation, demo, and educational purposes.

---

## 📁 Purpose

- Present a real fullstack application structure
- Showcase DevOps skills and infrastructure modularity
- Help others understand how frontend, backend, and infra are separated

---

## 🚫 Important

- No source code is included — only placeholders or empty files
- Sensitive files (like `.env`) are excluded
- Safe for public sharing and portfolio use

---

## 🧱 Folder Breakdown

### 🔹 `ProSkills-BE/` – Backend (FastAPI)

- `backend/`
  - `controllers/`, `middlewares/`, `dependencies/`, `models/`, `schemas/`, `services/`
  - `main.py`, `config.py`, `constants.py`, etc.
- `alembic/` – DB migrations for PostgreSQL
- `tests/` – unit/integration tests
- `docker-compose.yml`, `Dockerfile`, `.env.example`

### 🔹 `ProSkills-FE/` – Frontend (React + Vite)

- `src/`
  - `api/`, `components/`, `pages/`, `routes/`, `services/`, `store/`, `utils/`
- `public/`, `assets/`
- `App.tsx`, `vite.config.ts`, `.env.example`

### 🔹 `terraform/` – Infrastructure (AWS)

- `modules/` – modular Terraform setup:
  - `network/`, `security/`, `alb/`, `ecs/`, `cloudwatch/`, etc.
- `main.tf`, `variables.tf`, `terraform.tfvars`, `outputs.tf`
- ECS Fargate services, ALB, Cloud Map, ECR, Route53, S3

---

## 🧠 Use Cases

- Learn how to organize production-ready fullstack projects
- Reference template for your own backend/frontend/infra setup
- Showcase DevOps experience in interviews or public GitHub

---


