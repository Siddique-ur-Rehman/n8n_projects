# 📰 AI-Powered Daily LLM News Brief

## Overview

This n8n workflow automatically searches the web for the latest developments in Large Language Models (LLMs) and generates a concise daily news summary using AI. The summary is then sent directly to a Gmail inbox, keeping you updated on the newest AI trends, tools, research, and product releases.

## Features

- ⏰ Runs automatically on a scheduled interval.
- 🔍 Searches the web for the latest LLM-related news using SerpAPI.
- 🤖 Uses AI models (Google Gemini and Groq) to analyze and summarize information.
- 📧 Generates a professional email report with the latest updates.
- 🚀 Delivers AI news directly to your Gmail inbox.

## Technologies Used

- n8n
- Google Gemini
- Groq LLM
- SerpAPI
- Gmail API

## Workflow

1. The workflow starts on a scheduled trigger.
2. A predefined research topic is set.
3. The AI agent performs a real-time web search using SerpAPI.
4. Google Gemini and Groq process and summarize the latest information.
5. A professional news brief is generated.
6. The summary is automatically sent via Gmail.

## Requirements

- n8n instance
- SerpAPI API Key
- Google Gemini API Key
- Groq API Key
- Gmail OAuth Credentials

## Use Cases

- Stay updated with the latest AI and LLM advancements.
- Receive automated daily AI research summaries.
- Monitor new tools, models, and industry announcements.
- Build an AI-powered news monitoring and reporting system.

