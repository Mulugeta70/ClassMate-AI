# ClassMate-AI 🎓  
_AI-powered assistant for professors to grade assignments and give rich feedback._

## 📌 Overview

ClassMateAI is a web platform that helps professors:

- Create courses and assignments  
- Define grading rubrics  
- Let students submit essays (and later, code)  
- Use AI to generate suggested grades and feedback  
- Detect possible plagiarism between submissions  
- View a dashboard of student performance  
- Export grades to CSV for LMS import (Canvas, Moodle, etc.)

> ⚠️ AI is **assistive**, not final. Professors always have the final say on grades.

---

## ✨ Key Features (MVP)

- 👩‍🏫 **Professor Dashboard**
  - Create / manage courses
  - Create assignments with due dates
  - Build rubrics with multiple criteria

- 🧑‍🎓 **Student Portal**
  - View enrolled courses & assignments
  - Submit essays for assignments
  - View grades & feedback once released

- 🤖 **AI Grading & Feedback**
  - Uses the assignment rubric to:
    - Score each criterion
    - Generate per-criterion feedback
    - Suggest an overall score
  - Professors can review, edit, and approve final grades

- 🧪 **Plagiarism Risk Check (Basic)**
  - Compares submissions for the same assignment
  - Flags high similarity between student essays
  - Shows a plagiarism “risk” level to professors

- 📊 **Analytics Dashboard**
  - Average grade per assignment
  - Student overall performance
  - At-risk students (e.g., low average scores)

- 📁 **CSV Export**
  - Export final grades for easy import into an LMS

---

## 🏗️ Tech Stack

**Frontend**
- React or Next.js
- TypeScript
- Tailwind CSS

**Backend**
- Node.js + NestJS
- RESTful API
- JSON Web Tokens (JWT) for auth

**Database**
- PostgreSQL
- ORM: Prisma or TypeORM

**AI**
- LLM provider (e.g., OpenAI API) for:
  - Essay grading
  - Feedback generation
  - (Optional) Embeddings for similarity
