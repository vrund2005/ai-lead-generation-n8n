# 🚀 AI Lead Generation & Outreach Automation (n8n)

## 📌 Overview

This project automates the entire lead generation and outreach process using **n8n workflows, web scraping, and LLMs**.

It fetches leads, enriches company data, and generates **personalized 3-step email sequences** — fully automated.

---

## ⚙️ Workflow Architecture

* ⏰ Scheduled Trigger (daily execution)
* 🌐 Lead Fetching via Apify API
* 📊 Data Storage (Google Sheets)
* 🧠 Domain Extraction & Validation (custom JS logic)
* 🔎 Website Scraping + HTML Cleaning
* 🤖 Company Summary Generation (LLM)
* 📧 Personalized Email Sequence Generation (3-step outreach)
* 📈 Workflow Monitoring & Logging

---

## 🧠 Key Features

* End-to-end automation (no manual intervention)
* Context-aware email generation using LLMs
* Lead validation and domain extraction logic
* Error handling and logging pipeline
* Performance tracking (success rate, processed leads)

---

## 🛠 Tech Stack

* n8n (workflow automation)
* OpenAI API (LLM)
* Apify API (lead scraping)
* Google Sheets API
* JavaScript (custom nodes)

---

## 📂 Project Structure

```bash
.
├── workflow.json   # n8n workflow export
├── API_info.pdf
├── Workflow_Video.mp4
└── README.md
```

---

## 🚀 Setup Instructions

1. Import workflow into n8n
2. Configure:

   * OpenAI API key
   * Apify API key
   * Google Sheets credentials
3. Activate workflow

---

## 📊 Example Output

* Company summary (AI-generated)
* 3-step email outreach sequence
* Lead database with enrichment

---

## ⚠️ Limitations

* Depends on quality of scraped data
* LLM output may vary
* Requires API credits

---

## 🔮 Future Improvements

* Email sending automation (SMTP / SendGrid)
* Lead scoring using ML
* Multi-channel outreach (LinkedIn, etc.)

---

## 👨‍💻 Author

Vrund Patel
