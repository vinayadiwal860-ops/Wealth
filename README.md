# WealthAI

## Overview

WealthAI is a fintech super‑app that acts as an AI‑driven personal CFO for Indian users. The MVP includes a **Flutter** mobile front‑end, a **Node.js/TypeScript** back‑end, and infrastructure‑as‑code (Terraform) for AWS deployment.

---

### Quick Start (local development)

1. **Clone the repo** (or copy the folder).
2. **Frontend**
   ```bash
   cd frontend
   flutter pub get
   flutter run
   ```
3. **Backend**
   ```bash
   cd backend
   npm install
   npm run dev
   ```
4. **Docker** (optional) – bring up all services:
   ```bash
   docker-compose up --build
   ```

---

### Project Layout

```
wealthai/
├─ frontend/                # Flutter app
│   ├─ lib/                # Dart source
│   └─ pubspec.yaml
├─ backend/                # Node/TS services
│   ├─ src/                # Source code
│   └─ package.json
├─ infra/                  # Terraform IaC
├─ docker-compose.yml
└─ README.md
```

---

### License

MIT License – see [LICENSE](LICENSE) file.
