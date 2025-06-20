# 🧠 NeuroDesk – AI-Driven Customer Support & Issue Tracking System

NeuroDesk is a smart issue tracking and support system tailored for product-based companies. It leverages AI to improve ticket routing, reduce duplication, estimate criticality, and suggest possible solutions.

---

## 🔧 Tech Stack

### Backend:
- Java + Spring Boot (REST APIs, JWT auth, validations)
- MySQL / PostgreSQL
- Redis or ChromaDB (vector similarity)
- Spring Data JPA + Hibernate

### Frontend:
- React.js
- Material UI / Bootstrap

### AI/ML:
- Sentence Transformers (MiniLM)
- Redis / FAISS / ChromaDB for vector storage
- Cosine Similarity for duplicate detection
- OpenAI or HuggingFace (optional) for summarization

---

## 🔑 User Roles

| Role       | Permissions                                                      |
|------------|------------------------------------------------------------------|
| Customer   | Create/view tickets, edit, comment, rate                        |
| Support    | View, comment, assign, resolve tickets                          |
| Developer  | View/comment/resolve bugs assigned                              |
| Admin      | Full access, dashboard, reassignment, analytics                 |

---

## 📦 Modules Overview

1. **User & Role Management** (JWT Auth)
2. **Tool & Service Catalog** (Linked to teams/products)
3. **Ticket Management** (CRUD + comments + status flow)
4. **AI: Duplicate Ticket Detection** (Embeddings + cosine)
5. **AI: Suggested Resolution** (LLM-based summary from history)
6. **AI: Auto Assignment** (based on skills, history, reviews)
7. **AI: Criticality Estimation** (priority classification)
8. **Dashboard & Analytics** (volume, time, ratings, etc.)

---

## 🚧 Current Progress

- ✅ Project initialized in Spring Boot
- ✅ Folder structure created
- ⏳ User Auth module in progress
- ⏳ Ticket schema designed
- ⏳ Embedding logic planning

---

## 🗓️ Week-by-Week Execution Plan (see PDF)
- Week 1: Auth + User Roles + Ticket schema
- Week 2: Similar Ticket AI engine
- Week 3: Ticket status flow + assignment engine
- Week 4: Dashboard + cleanup + polish

---

## 🧪 Bonus Goals
- Dockerized setup
- Slack/email notifications
- Language translation for tickets
