# ResumeForge - AI Cover Letter & Resume Summary Generator

An intelligent n8n automation that generates personalized cover letters and resume summaries using AI.

##  Features

- Accepts Job Post (PDF, Image, or Text)
- Accepts Resume (PDF or Text)
- AI-powered analysis using OpenAI + Gemini
- Generates professional Cover Letter (HTML + PDF)
- Generates optimized Resume Summary (HTML + PDF)
- Automatically emails the generated documents
- Webhook integration ready for web app

##  Tech Stack

- n8n Workflow Automation
- OpenAI (GPT-4o-mini)
- Google Gemini
- PDF Generator API
- Gmail
- Webhook Trigger

## How to Use

1. Download `resumeforge-ai-coverletter-summary.json`
2. Import into n8n
3. Configure credentials (OpenAI, Gemini, Gmail, PDF Generator)
4. Activate the workflow
5. Use the webhook URL in your web application

## Workflow Overview

Webhook Trigger → File Processing → AI Analysis → Cover Letter Generation → Resume Summary Generation → PDF Conversion → Email Delivery

## 🌐 Live Web Application
- **Website**: [https://resumeforge-bice-chi.vercel.app]
- Features: Supabase Authentication, File Upload, Document History

NOTE:This website is for test and learning purpose.I used free limited version tools. If you face any error or unexpected result, pardon me.
