📌 Automated Feedback Collection & Email Response Workflow (n8n)

This repository contains an n8n workflow designed to automate the complete process of collecting student feedback, analyzing sentiment, and sending personalized response emails using Google Sheets, Gmail, and Google Gemini AI.

🚀 Features
🔹 1. Automated Email Sending (Every 2 Weeks)

A scheduled trigger sends a feedback request email to all students listed in a Google Sheet using Gmail integration.

🔹 2. Google Sheets Monitoring

A Google Sheets Trigger listens for new feedback submissions and instantly processes the response.

🔹 3. Sentiment Analysis

The workflow uses Google Gemini AI (via LangChain) to analyze each review and determine the sentiment (positive/negative/neutral).

🔹 4. AI-Generated Personalized Response Emails

Based on the feedback sentiment:

Gemini generates a custom response email for each student.

The email is automatically sent through Gmail.

🔹 5. Multi-Layer Workflow Logic

Includes:

Schedule Trigger

Gmail Send nodes

Google Sheets read/write

Sentiment Analysis node

Multiple LLM chains

Google Gemini Chat Models

🛠️ Technologies Used

n8n (Automation platform)

Google Sheets API

Gmail API

LangChain

Google Gemini (PaLM)

JavaScript Functions (Inside n8n)
