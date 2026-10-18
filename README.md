# Carlos Gil — Personal Engineering Portfolio Website

[![GitHub Pages Deployment](https://img.shields.io/badge/Deployment-GitHub_Pages-22c55e.svg)](https://quiquecg.github.io)
[![Stack](https://img.shields.io/badge/Stack-HTML5_|_Tailwind_CSS_|_JavaScript-0ea5e9.svg)](https://quiquecg.github.io)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

The official personal engineering portfolio and project showcase for **Carlos Gil Roa** (Senior Data Engineer & AI-Native Systems Builder), hosted on **GitHub Pages** at:

👉 **[https://quiquecg.github.io](https://quiquecg.github.io)**

---

## 1. Overview & Architecture

This repository contains a high-performance, responsive static website designed to showcase production data engineering, semantic modeling, and AI-native initiatives to hiring managers, technical interviewers, and engineering clients:

* **Zero-Dependency Static Delivery**: Built with modern semantic HTML5 and Tailwind CSS (via CDN) with zero Node/Ruby build pipelines, ensuring instant initial load (< 400ms) and 100% uptime on GitHub Pages.
* **Interactive Project Showcase**: Dynamic client-side category filtering (`Semantic Layer & BI`, `Data Engineering`, `AI & LLM Agents`).
* **Direct Asset Hosting**: Serves the aligned PDF Resume/CV directly from `/assets/CV_Carlos_Gil_Data_Engineer.pdf` with single-click download capabilities.
* **Responsive Dark UI**: Modern dark theme with subtle neon glow borders and glassmorphism headers optimized across mobile, tablet, and desktop screens.

---

## 2. Featured Projects Showcased

1. **[Wallet LookML](https://github.com/quiquecg/wallet-lookml)**: Enterprise LookML semantic layer on Google BigQuery, implementing symmetric aggregate joins, datagroup caching, Two-Tier accounting measures, and automated AST linting in GitHub Actions.
2. **[Wallet Financial Lakehouse](https://github.com/quiquecg/wallet)**: Multi-currency Medallion Lakehouse with automated email alert ingestion (IMAP) and BudgetBakers API integration, DuckDB querying, and real-time TRM currency normalization.
3. **AI-Native Semantic Query Agent & RAG**: Autonomous tool-calling microservice querying enterprise data dictionaries, natural-language-to-SQL translation, and production FastAPI endpoints.
4. **Distributed Big Data Computing (PySpark)**: Large-scale analytics research at the University of Padua exploring memory tuning, broadcast joins, and process mining telemetry under GDPR/SOC 2 standards.

---

## 3. Local Development & Preview

To preview the website locally in any browser:

```bash
# Option 1: Python built-in HTTP server
cd C:\projects\quiquecg.github.io
python -m http.server 8000
# Then open http://localhost:8000 in your browser

# Option 2: Open directly
start index.html
```

---

## 4. Deployment Instructions

This repository is designed to be hosted directly on **GitHub Pages** using GitHub's user site mechanism (`<username>.github.io`):

```bash
cd C:\projects\quiquecg.github.io
git init
git add .
git commit -m "feat: initial release of personal engineering portfolio website"
git branch -M main
git remote add origin https://github.com/quiquecg/quiquecg.github.io.git
git push -u origin main
```

Once pushed to GitHub:
1. Navigate to repository **Settings** -> **Pages**.
2. Under **Build and deployment**, ensure **Source** is set to `Deploy from a branch` with branch `main` and folder `/ (root)`.
3. The site will automatically go live at **`https://quiquecg.github.io`**.
