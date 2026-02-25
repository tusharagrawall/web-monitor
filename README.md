# Personal Web Monitor + AI Summary

A MERN-stack web application that monitors webpages for changes and generates AI-powered summaries of those changes.

---

## 🚀 Features Implemented

- Add URLs to monitor
- Delete monitored URLs
- Fetch webpage content
- Detect changes using diff logic
- Generate AI summaries of changes (Groq LLM)
- View last 5 checks per URL
- Status page:
  - Server health
  - Database health
  - LLM connectivity
- Basic input validation
- Timeout handling for slow websites
- Colored diff UI (Git-style)
- Clean responsive UI

---

## 🏗 Tech Stack

Frontend:
- React (Vite)
- Axios
- Plain CSS

Backend:
- Node.js
- Express
- MongoDB (Mongoose)
- Cheerio (HTML parsing)
- diff (change detection)
- Groq API (LLM summaries)

Database:
- MongoDB Atlas

---

## ⚙️ How To Run Locally

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd <repo-name>
