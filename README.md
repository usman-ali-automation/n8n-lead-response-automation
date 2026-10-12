# n8n Lead-Response Automation

An end-to-end n8n workflow that captures inbound leads, classifies them with AI, and responds automatically — so no lead goes unanswered.

## What It Does

- Captures leads via webhook (works with any form, ad, or website)
- Validates phone and email data with JavaScript
- Uses Google Gemini to classify urgency (HOT / NORMAL)
- Sends an instant personalized email reply
- Alerts the owner when a hot lead arrives
- Logs every lead to Google Sheets
- Follows up automatically if the lead goes quiet

## Stack

n8n · Google Gemini · Gmail · Google Sheets · JavaScript · Webhooks

## How to Use

1. Download `lead-response-workflow.json`
2. In n8n: **Import from File**
3. Reconnect your own credentials (Gmail, Google Sheets, Gemini API)
4. Update the webhook URL in your lead source

## Note

All credentials, IDs, and personal data have been removed from this export. You will be prompted to connect your own accounts on import.

## Author

Usman Ali — AI Automation Developer
[LinkedIn](https://www.linkedin.com/in/usman-ali-0a49273a0) · [GitHub](https://github.com/usman-ali-automation)
