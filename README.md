# Reglemento — Regulatory Monitoring Platform

**Reglemento** is an intelligent platform that monitors and summarizes legal and regulatory changes from European and national sources. It provides real-time alerts and actionable summaries tailored to SMEs, freelancers, and compliance officers.

---

## 🌟 Key Features
- 📰 Automated scraping of official regulatory sources (EU, national gazettes, public websites).
- 🔔 Personalized notifications based on user profiles.
- 📝 Summarization of legal documents into clear tasks and obligations.
- 📊 Compliance dashboard to track obligations and deadlines.
- 🔒 Secure authentication & authorization using Auth0.

---

## 🏗️ Tech Stack

| Layer                  | Technology                          |
|------------------------|-------------------------------------|
| Frontend (SPA)          | Angular 17                         |
| Backend API             | .NET 8 Web API (CQRS, DDD)         |
| Scraping Microservice   | Python FastAPI                     |
| Authentication          | Auth0                              |
| Database                | PostgreSQL                         |
| Notifications           | Email (Future: Push Notifications) |

---

## 📂 Project Structure

/frontend -> Angular Web Application
/backend -> .NET 8 API Services
/scraper-service -> Python FastAPI microservice for scraping
/infra -> CI/CD pipelines & deployment configurations
/docs -> Documentation (LaTeX, C4 Diagrams, Data Schemas)


---

## 🚀 Installation & Development Setup

### Prerequisites
- Node.js (v18+)
- .NET 8 SDK
- Python 3.10+
- PostgreSQL (local or Docker)
- Auth0 account (free tier)

### Clone the repository
```bash
git clone https://github.com/your-username/reglemento.git
cd reglemento
```

### Frontend Setup (Angular)
```bash
cd frontend
npm install
npm start
```

### Backend API (.NET 8)
```bash
cd backend
dotnet restore
dotnet run
```

### Scraper Service (Python FastAPI)
```bash
cd scraper-service
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 🌐 API Documentation
- Backend API (.NET): Swagger available at /swagger
- Scraper Service (FastAPI): Swagger UI at /docs

---

## 🗂️ Documentation
All technical documentation, C4 diagrams, database schemas, and architecture decisions are located in the /docs folder. The documentation is written in LaTeX and exported in PDF.

---

## 🤝 Contributing
Contributions are welcome! Please open issues for bugs, feature requests, or improvements.
1) Fork the repo
2) Create a feature branch
3) Commit changes
4) Open a Pull Request 🚀

---

## 📄 License
This project is licensed under the MIT License.

---

## 💡 Vision
Reglemento aims to simplify compliance processes for small businesses by offering an affordable and user-friendly regulatory monitoring solution.
