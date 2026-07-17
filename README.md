# AuraBuild AI 🚀

## 🚧 Project Status: Active Development
*This repository is currently being migration-managed from a local development environment. Core structural layouts and architecture placeholders are live; complete codebase deployment and production live links are scheduled for release shortly.*

---

An AI-driven full-stack site generator that instantly converts natural language prompts into live, responsive website layouts. Built using the PERN (PostgreSQL, Express.js, React.js, Node.js) stack.

## 🌟 Key Features
- **Prompt-to-UI Generation:** Translates user text prompts into clean, responsive HTML/Tailwind layouts via AI parsing models.
- **Real-Time Synchronization:** Utilizes an optimized PostgreSQL relational schema to keep client-side component states perfectly in sync with user configurations.
- **State Management:** Handled via custom state architectures for low-latency configuration updates.

## 🛠️ Tech Stack
- **Frontend:** React.js / Next.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (with optimized schema indexing)

## 📊 Database Architecture
The PostgreSQL schema is structured for real-time responsiveness:
- `users`: Manages authentication and user sessions.
- `layouts`: Stores component structures, state trees, and raw configurations linked via foreign keys for sub-100ms relational querying.
