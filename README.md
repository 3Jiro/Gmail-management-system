# 📧 Intelligent Gmail Triage & Draft Engine
### 🌟 Overview
An automated email management system that uses multi-stage classification to eliminate "Inbox Noise." This workflow categorizes incoming mail into functional buckets and uses an LLM to pre-draft contextually relevant responses for personal and sales inquiries.

### 🛠️ Technical Architecture
- **Rule-Based Routing:** Uses a custom "Switch" node to sort emails into five distinct categories (Promotions, Social, Personal, Sales, Misc).

- **LLM Draft Generation:** Triggers a Gemini-powered prompt for "Personal" emails, generating a natural-language draft based on the original thread context.

- **Inbox Cleanliness:** Automatically marks categorized mail as read and applies specific labels to ensure the primary inbox remains at "Zero."

### ⚙️ Tech stack
- **Primary Engine:** n8n (self hosted) / Gmail API
- **AI/LLM:** Google gemini / OpenAI
- **Communication:** Gmail
