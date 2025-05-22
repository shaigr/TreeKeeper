# 🌳 TreeKeeper

**A privacy-first, open-source genealogy tree app you can run offline or online.**

---

## 🛡️ Why TreeKeeper?

Most genealogy tools are:
- ❌ Online-only
- ❌ Require paid subscriptions
- ❌ Collect your family’s private data

**TreeKeeper** is:
- ✅ Free & open-source
- ✅ Fully offline or self-hosted
- ✅ Password-protected
- ✅ Simple to use and extend

---

## ✨ Features (MVP)

- 🧬 Create & manage family trees
- 🔐 Local authentication (login/password)
- 🗂️ Save data locally (e.g., JSON or SQLite)
- 📁 Export/import in GEDCOM (genealogy standard)
- 📡 Optional self-hosted web version

---

## 🔧 Tech Stack (Proposed)

| Layer      | Tech                          |
|------------|-------------------------------|
| Frontend   | React / Svelte / Tauri        |
| Backend    | Rust (Rocket) / Python (FastAPI) |
| Storage    | SQLite / Local JSON           |
| Auth       | JWT or Cookie Sessions        |
| Deploy     | Docker (optional)             |

---

## 🚀 Getting Started (Concept)

```bash
git clone https://github.com/shaigr/treekeeper
cd treekeeper
# Backend
cd backend && cargo run  # or `uvicorn main.py` for Python
# Frontend
cd frontend && npm run dev

## 🎯 Roadmap Ideas

🧩 Invite other family members securely
🌐 Multi-language support
🧠 AI: Relationship suggestions via LLM
📷 Face recognition for old photos
🙌 Contributing

Contributions, issues, and ideas welcome!

📄 License

MIT
