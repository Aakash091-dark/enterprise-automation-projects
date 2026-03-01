# NEWS Scraper – Multi-Source News Aggregation Engine

## 📌 Overview

NEWS Scraper is a modular Python-based system designed to collect, process, and structure news articles from RSS feeds and targeted sources.

The system integrates scraping, similarity analysis, and structured reporting.

> Note: Source code excluded due to confidentiality agreements.

---

## 🎯 Problem Statement

Manual monitoring of news sources creates inefficiencies and duplicate content issues.

The objective was to build:

- Automated RSS ingestion
- Structured article processing
- Deduplication using text similarity
- Reporting for failed links

---

## 🏗 Architecture Approach

RSS Feed
→ Source-Specific Scraper
→ Text Processor
→ Cosine Similarity Deduplication
→ Structured Output
→ Reporting & Logs

---

## 🛠 Tech Stack

- Python
- RSS Parsing Utilities
- Cosine Similarity (Text comparison)
- Logging utilities
- GitHub Actions (CI/CD ready)

---

## 🔹 Key Contributions

- Implemented RSS ingestion pipelines
- Designed cosine similarity-based deduplication
- Built structured failure tracking system
- Created modular scraper package
- Integrated CI/CD workflow

---

## 📈 Impact

- Reduced duplicate article storage
- Automated multi-source content aggregation
- Improved reliability through logging & failure reports
