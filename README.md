🚀 SmartPolicy

AI-Powered Compliance Automation Platform

SmartPolicy is an intelligent compliance enforcement system that transforms static policy documents into executable validation logic and automatically applies them to operational datasets.

Built during HackFest 2.0
Designed to demonstrate AI-driven policy ingestion, rule extraction, and automated dataset validation.

🔗 Project Structure

This project is organized into two independent repositories:

🧠 Backend (API + AI Engine)

FastAPI | MongoDB | OpenAI | Rule Engine

👉 Repository:
https://github.com/Sakhaa-Digital/GDG_Backend

Handles:

Policy ingestion (PDF/Image/Text)

AI-based rule extraction

Embedding generation

CSV dataset processing

Rule evaluation engine

Violation storage & reporting

Background processing

🎨 Frontend (User Interface)

React.js | Firebase Auth | UI Dashboard

👉 Repository:
https://github.com/Sakhaa-Digital/GDG_Frontend

Handles:

Admin authentication (Google Auth via Firebase)

Policy upload interface

CSV dataset upload

Dataset status tracking

Violation viewing dashboard

Clean UI for compliance monitoring

🧩 What Problem Does SmartPolicy Solve?

Organizations maintain detailed compliance policies, but enforcing them manually against operational data is:

Time-consuming

Error-prone

Reactive instead of proactive

SmartPolicy automates this process by:

Extracting structured rules from uploaded policies using AI

Converting those rules into executable validation logic

Automatically evaluating uploaded datasets (CSV files)

Generating structured violation reports

This bridges the gap between written compliance policies and real-time operational enforcement.

⚙️ Core Features

📄 Policy document ingestion (PDF, image, text)

🤖 AI-powered structured rule extraction

🧠 Embedding-based policy chunk storage

📊 CSV dataset upload with background processing

⚙️ Automated rule evaluation engine

🚨 Violation detection with severity levels

📈 Dataset processing status tracking

🔐 Google authentication (Firebase)

🏗️ System Architecture (High-Level)
Policy Upload
      ↓
AI Rule Extraction
      ↓
Structured Rule Storage (MongoDB)
      ↓
CSV Dataset Upload
      ↓
Background Processing
      ↓
Rule Evaluation Engine
      ↓
Violation Reports
💡 Example Use Cases

Anti-Money Laundering (AML) transaction monitoring

HR attendance & leave compliance

Data retention and privacy enforcement (GDPR-style)

Internal audit automation

Regulatory compliance validation

🛠 Tech Stack
Backend

FastAPI

MongoDB

OpenAI API (LLM + Embeddings)

Cloudinary (File Storage)

Pandas (Dataset Processing)

Async Background Tasks

Frontend

React.js

Firebase Authentication

Modern Dashboard UI

📌 Hackathon Submission

This project was built and submitted for:

HackFest 2.0
