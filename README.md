# 🧮 FastAPI Calculator

[![CI](https://github.com/kk795-NJIT/IS601_Module8/actions/workflows/test.yml/badge.svg)](https://github.com/kk795-NJIT/IS601_Module8/actions/workflows/test.yml)

A small, professional **FastAPI Calculator** featuring a web UI, REST API, structured logging, and automated testing with full CI/CD integration.

**Status:** ✅ Production Ready | **Version:** v1.0.0 | **License:** MIT

---

## 📋 Overview

- Four operations: **Add**, **Subtract**, **Multiply**, **Divide**
- Web UI at [http://localhost:8000](http://localhost:8000)
- REST API with **validation** and **error handling**
- **Division-by-zero** protection
- Logging to both **console** and **app.log**
- **Unit**, **Integration**, and **E2E** tests (with Playwright)
- Automated **CI/CD** using GitHub Actions

---

## 🚀 Quick Start

### 1️⃣ Clone and Set Up

```bash
git clone https://github.com/kk795-NJIT/IS601_Module8.git
cd IS601_Module8
python -m venv venv
source venv/bin/activate        # macOS/Linux
# or
venv\Scripts\activate           # Windows
pip install -r requirements.txt