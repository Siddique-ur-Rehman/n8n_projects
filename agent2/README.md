# 💬 AI Chatbot with Sentiment Analysis

## Overview

This n8n workflow combines an AI chatbot with sentiment analysis to understand user conversations and automatically categorize responses as **positive**, **neutral**, or **negative**. Each conversation is analyzed and stored in the appropriate Google Sheet for tracking and future analysis.

## Features

- 💬 AI-powered chatbot using Google Gemini.
- 🧠 Maintains short-term conversation memory for better responses.
- 😊 Performs automatic sentiment analysis on AI interactions.
- 📊 Stores positive, neutral, and negative conversations in separate Google Sheets.
- 📅 Includes date and time information for conversation tracking.

## Technologies Used

- n8n
- Google Gemini
- Google Sheets API
- AI Sentiment Analysis
- Memory Buffer

## Workflow

1. A user sends a message to the chatbot.
2. Google Gemini generates an AI response.
3. The conversation is analyzed for sentiment.
4. The result is classified as Positive, Neutral, or Negative.
5. The conversation is automatically saved to the corresponding Google Sheet.

## Requirements

- n8n instance
- Google Gemini API Key
- Google Sheets OAuth Credentials

## Use Cases

- Customer support chat analysis.
- User feedback monitoring.
- AI conversation logging.
- Customer satisfaction tracking.
- Sentiment-based analytics and reporting.

