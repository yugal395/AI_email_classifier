# AI Email Classifier Automation

This project demonstrates a simple AI-powered workflow built with **n8n** and **Google Gemini API**.

## Workflow

Email input → AI classification → automated routing

The system classifies emails into:

- support
- sales
- complaint
- spam
- other

Based on the classification, the workflow routes the message to different Slack channels.

## Technologies Used

- n8n (workflow automation)
- Google Gemini API
- JSON API requests
- Slack integration

## How It Works

1. An email is received (simulated using a Set node).
2. The email content is sent to the Gemini LLM via API.
3. The AI classifies the email category.
4. A Switch node routes the email to the correct Slack channel.

## Purpose

This project demonstrates how AI models can be integrated into automation workflows to assist with tasks like:

- support ticket routing
- lead classification
- complaint detection

## Author

Yugal
