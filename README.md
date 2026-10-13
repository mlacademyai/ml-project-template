# ML Project Template

> **TL;DR** — Template project Machine Learning yang well-structured, modular, reproducible, dan production-ready. Based on lessons learned dari 10+ industrial ML projects.

---

## 🔬 Purpose

Machine learning projects aren't just about training models. You deal with:

- Multiple versions of datasets
- Experimental code evolving into production workflows
- Model artifacts that must be versioned and tracked
- Complex pipelines from raw data to predictions

**This template shows how to organize ML projects like professional software:**

- Modular structure (src/, configs/, tests/)
- Reproducible pipelines
- Production-ready workflows

---

## 🏗️ Project Structure

```
├── config/              # Configuration files
├── notebooks/           # Jupyter notebooks (EDA, prototyping)
├── src/                 # Source code (data processing, modeling)
├── tests/               # Unit tests
├── images/              # Documentation images
├── requirements-*.txt   # Dependencies
├── Dockerfile           # Container definition
├── docker-compose.yml   # Local dev environment
└── Makefile             # Task automation
```

---

## 🛠️ Tech Stack

- Python
- Docker & Docker Compose
- Jupyter
- Pytest (testing)
- MLOps tools (configurable)

---

## 🚀 Getting Started

```bash
# Clone and setup
git clone https://github.com/henryferdianto/ml-project-template.git
cd ml-project-template

# Using Docker
docker-compose up -d

# Or local
pip install -r requirements-prod.txt
make help
```

---

## ⚠️ Notes

- This is a **template/fork** from upstream (mlacademyai/ml-project-template)
- Customize `config/` and `src/` based on your project needs
- Add your own data processing and modeling logic

---

## 📜 License

MIT License — see [LICENSE](LICENSE).