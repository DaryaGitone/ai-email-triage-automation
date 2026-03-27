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

<img width="1734" height="313" alt="Job Application Flow" src="https://github.com/user-attachments/assets/afc276b0-2ba6-4684-a5e8-724df8aceb8c" />

*The end-to-end automation logic in Make.*

### 2. Structured Database

<img width="1559" height="149" alt="Job Applications Table" src="https://github.com/user-attachments/assets/832d6000-69d1-48b7-b8a6-9325c69a5593" />

*Clean, deduplicated data ready for analysis.*

<img width="983" height="438" alt="Job Application in Google Tasks" src="https://github.com/user-attachments/assets/f65c3291-afb7-4dd7-93ad-2ed1918988fd" />

---

## 💡 Key Challenges Solved
* **Handling Unstructured Data:** Using AI to turn messy email text into organized rows.
* **Data Integrity:** Implementing a search-and-filter logic to avoid double-posting the same email.
* **Loop Closing:** Moving from "reading an email" to "active task management" without human intervention.# ai-email-triage-automation
AI-powered workflow that automates email triage: extracts data using OpenAI (GPT), parses JSON, deduplicates entries, and schedules follow-ups in Google Tasks via Make.com.
