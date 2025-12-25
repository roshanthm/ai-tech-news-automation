# AI & Tech News Automation 🚀

An automated system that fetches **AI and Tech news separately**, summarizes the content using **Google Gemini**, and delivers clean daily email updates using **Gmail OAuth**.

Built as part of my hands-on learning with **LLMs, workflow automation, and real-world integrations**.

---

## 🔍 What This Project Does

This automation runs on a schedule and:

- Fetches news from **AI-specific RSS feeds**
- Fetches news from **Tech-related RSS feeds**
- Aggregates and removes duplicate articles
- Uses **Google Gemini (LLM)** to summarize content
- Sends **separate daily emails** for:
  - 🧠 AI News
  - 💻 Tech News

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **Google Gemini (gemini-2.5-flash)** – News summarization
- **RSS Feeds** – News source
- **Gmail OAuth2 API** – Email delivery
- **Prompt Engineering** – Structured email summaries

---

## 🧠 Workflow Overview

1. **Schedule Trigger**
   - Runs daily at a fixed time

2. **RSS Feed Reader**
   - AI news feeds
   - Tech news feeds (separate workflow)

3. **Data Aggregation**
   - Combines and deduplicates articles

4. **LLM Summarization**
   - Gemini analyzes articles
   - Produces clean, email-ready summaries

5. **Email Sending**
   - Sends formatted summaries via Gmail

---

## ✉️ Email Format

Each email includes:

- Clear subject line
- Headlines in ALL CAPS
- 2–3 sentence summaries
- Direct article links
