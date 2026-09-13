# 🤖 n8n Automated Motivational Quotes Pipeline

An end-to-end AI automation pipeline that fetches subscribers from Airtable, generates dynamic motivational quotes via Google Gemini API, filters dynamic email records, and dispatches daily emails via Gmail.

## 🛠 Tech Stack
- **Orchestration:** n8n
- **LLM Engine:** Google Gemini API
- **Database:** Airtable
- **Delivery:** Gmail API

## 📋 Architecture Flow
1. **Cron Trigger:** Fires every day at 6:00 AM.
2. **AI Agent:** Queries Gemini model for custom quotes.
3. **Database Query:** Retrieves contact list from Airtable.
4. **Data Sanitization:** Filters and loops dynamic email records.
5. **Gmail Node:** Sends personalized output.

