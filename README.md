# Web‑based Customer Support System

A Java Spring Boot + SQL web app for ticketing, notifications, feedback, analytics, and knowledge base.

## 🎯 Objectives
- Submit & track support tickets
- Assign & prioritize work
- Notify users & staff
- Capture feedback
- Basic analytics dashboard

## 🧱 Tech Stack
- Backend: Spring Boot (Java 17+), JPA/Hibernate
- DB: MySQL/PostgreSQL (pick one)
- Build: Maven or Gradle
- Auth: Spring Security (session/JWT)
- (Optional) Frontend: React + Vite

## 🚀 Quick Start (Dev)
```bash
# 1) Clone
git clone https://github.com/<org-or-user>/customer-support-system.git
cd customer-support-system/backend

# 2) Configure DB: copy example and edit values
cp src/main/resources/application.properties.example src/main/resources/application.properties

# 3) Run (Maven example)
./mvnw spring-boot:run
