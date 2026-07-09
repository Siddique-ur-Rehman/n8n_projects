# 📄 AI Resume Screening & Candidate Evaluation System

## Overview

This n8n workflow automates the resume screening process by comparing uploaded resumes against a job description using Google Gemini. It evaluates candidate qualifications, assigns a score, identifies strengths and gaps, stores the results in Google Sheets, and sends a notification email when the evaluation is complete.

## Features

- 📂 Automatically detects new resumes uploaded to Google Drive.
- 📄 Extracts text from resumes and job descriptions.
- 🤖 Uses Google Gemini to evaluate candidate suitability.
- 📊 Generates detailed candidate scores and hiring recommendations.
- 📑 Parses AI responses into structured data.
- 📈 Stores evaluation results in Google Sheets.
- 📧 Sends an email notification after processing.

## Technologies Used

- n8n
- Google Drive API
- Google Gemini
- Google Sheets API
- Gmail API

## Workflow

1. A new resume is uploaded to a Google Drive folder.
2. The resume and job description are downloaded and processed.
3. Text is extracted from both documents.
4. Google Gemini compares the resume with the job description.
5. The AI generates candidate scores, strengths, gaps, and recommendations.
6. The results are formatted and stored in Google Sheets.
7. A confirmation email is sent automatically.

## Requirements

- n8n instance
- Google Drive OAuth Credentials
- Google Gemini API Key
- Google Sheets OAuth Credentials
- Gmail OAuth Credentials

## Use Cases

- Automated resume screening.
- AI-powered candidate evaluation.
- HR and recruitment automation.
- Applicant Tracking System (ATS) support.
- Candidate scoring and reporting.


