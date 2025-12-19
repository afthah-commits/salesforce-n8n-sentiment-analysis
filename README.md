# Salesforce Case Sentiment Analysis using n8n & OpenAI

This project demonstrates an automated workflow built using **n8n**, **Salesforce**, and **OpenAI** to analyze customer sentiment from Salesforce case records.

## 🔍 Workflow Overview
- A Salesforce Case is created
- n8n triggers automatically
- Case Subject & Description are sent to OpenAI
- Sentiment is classified as:
  - Positive
  - Neutral
  - Negative
- Based on sentiment, an automated email is sent via Gmail

## 🛠 Tech Stack
- Salesforce
- n8n
- OpenAI
- Gmail

## 📂 Files
- `salesforce-sentiment-analysis.json` – Exported n8n workflow

## 🚀 How to Use
1. Import the JSON file into your n8n instance
2. Configure credentials:
   - Salesforce
   - OpenAI
   - Gmail
3. Activate the workflow
4. Create a Salesforce Case to test

## ⚠️ Notes
- No credentials are included
- Users must configure their own API keys

## 📌 Use Cases
- Customer support automation
- AI-powered CRM insights
- Faster response handling
