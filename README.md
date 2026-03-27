# 📧 AI-Powered Email Triage & Automation Workflow

An intelligent automation system built with **Make.com** and **OpenAI** to transform unstructured email data into a structured tracking system. This workflow eliminates manual data entry and ensures consistent follow-ups.

---

## 🚀 How it Works

1.  **Trigger:** Monitors Gmail for specific incoming applications or leads.
2.  **AI Analysis:** Uses **OpenAI (GPT)** to read the email body and extract key information (Company, Role, Date).
3.  **Data Structuring:** Converts AI output into a clean **JSON** format.
4.  **Deduplication:** Searches Google Sheets for the unique `Message ID` to prevent duplicate logs.
5.  **Logging:** Records structured data into Google Sheets.
6.  **Task Scheduling:** Automatically creates a **Google Task** to remind me to follow up in 7 days.

---

## 🛠 Tech Stack

* **Automation Platform:** Make.com (formerly Integromat)
* **AI:** OpenAI API (GPT-4/3.5)
* **Data Handling:** JSON & Regular Expressions
* **Database:** Google Sheets
* **Task Management:** Google Tasks

---

## 📸 Project Preview

### 1. Workflow Architecture
![Make Workflow](ссылка_на_твое_первое_фото)
*The end-to-end automation logic in Make.*

### 2. Structured Database
![Google Sheets](ссылка_на_твое_второе_фото)
*Clean, deduplicated data ready for analysis.*

---

## 💡 Key Challenges Solved
* **Handling Unstructured Data:** Using AI to turn messy email text into organized rows.
* **Data Integrity:** Implementing a search-and-filter logic to avoid double-posting the same email.
* **Loop Closing:** Moving from "reading an email" to "active task management" without human intervention.# ai-email-triage-automation
AI-powered workflow that automates email triage: extracts data using OpenAI (GPT), parses JSON, deduplicates entries, and schedules follow-ups in Google Tasks via Make.com.
