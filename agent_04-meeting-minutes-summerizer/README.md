# 📝 AI Meeting Transcript Summarizer

## Overview

This n8n workflow automatically converts a meeting transcript into well-structured meeting minutes using AI. It extracts the transcript from a file stored in Google Drive, generates a meeting summary, action items, key decisions, and a professional follow-up email, then sends the results directly via Gmail.

## Features

- 📂 Downloads meeting transcripts from Google Drive.
- 📄 Extracts text from transcript files automatically.
- 🤖 Uses AI (Google Gemini and Groq) to analyze meeting discussions.
- 📝 Generates structured meeting minutes.
- ✅ Identifies action items, owners, priorities, and deadlines.
- 📌 Highlights key decisions made during the meeting.
- 📧 Creates and sends a professional follow-up email automatically.

## Technologies Used

- n8n
- Google Drive API
- Google Gemini
- Groq LLM
- Structured Output Parser
- Gmail API

## Workflow

1. Manually start the workflow.
2. Download the meeting transcript from Google Drive.
3. Extract the transcript text.
4. AI analyzes the discussion and generates:
   - Meeting Summary
   - Action Items
   - Key Decisions
   - Follow-up Email
5. Format the response using a structured output parser.
6. Send the meeting minutes via Gmail.

## Requirements

- n8n instance
- Google Drive OAuth Credentials
- Google Gemini API Key
- Groq API Key
- Gmail OAuth Credentials

## Use Cases

- Automatic meeting minutes generation.
- Team meeting documentation.
- Project status meeting summaries.
- Client meeting follow-up emails.
- AI-powered meeting management and reporting.

