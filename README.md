# mvp-generator

A **CLI tool for generating MVP applications using LLM (GPT-4o)**.

- Generates **FastAPI/Next.js** projects from plain-text prompts.
- Saves generated project structure in `generated_projects/`.
- Prepares projects for **Docker deployment**.
- Designed for **fast prototyping and launch validation**.

---

## 🚀 Features

✅ Generate backend (FastAPI) and frontend (Next.js / Streamlit) structures.  
✅ Automatic prompt sending to LLM and code saving.  
✅ Lightweight CLI using `typer` for cross-platform usability.  
✅ Structure ready for Docker Compose deployment.  
✅ Supports `.env` for secure key management.

---

## 🛠️ Installation

1️⃣ Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/mvp-generator.git
cd mvp-generator
```

2️⃣ Create and activate a virtual environment:
```bash
python3.12 -m venv .venv
source .venv/bin/activate  # Linux/macOS
.\.venv\Scripts\activate   # Windows
```

3️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

4️⃣ Create `.env`:
```
OPENAI_API_KEY=your_key_here
```

---

## ⚡ Usage

Basic usage:
```bash
python main.py generate "Create a FastAPI CRUD app for notes with SQLite"
```

Options will include:
- Select backend only, frontend only, or full-stack.
- Specify output directory.
- View generation logs.

---

## 🛣️ Roadmap

- [ ] Initial CLI implementation.
- [ ] Docker Compose integration.
- [ ] Streaming output for large file generation.
- [ ] Frontend for managing requests and downloads.
- [ ] Stripe/Gumroad monetization integration.
- [ ] Prompt caching for cost optimization.
- [ ] Testing and CI/CD pipeline with GitHub Actions.

---

## 🧩 Contributing

Pull requests, issues, and feedback are welcome.

---

## 📜 License

MIT License.

---

## 📞 Contact

For questions or collaboration:
- Telegram: [YOUR TELEGRAM]
- Email: [YOUR EMAIL]

---

## ✅ Status

Preparing the development environment for the MVP phase.
