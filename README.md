---
title: Resume Chatbot
emoji: ⚡
colorFrom: yellow
colorTo: green
sdk: gradio
sdk_version: 5.44.0
app_file: app.py
pinned: false
short_description: 'An AI-powered chatbot that acts as a virtual representative '
---

# Project Structure
 - app.py – Main application logic
 - resume.pdf – Resume used for profile extraction
 - requirements.txt – Python dependencies

# Resume Chatbot ⚡

An AI-powered chatbot that acts as a virtual representative for Manav Patel, answering questions about his career, background, skills, and experience.

## Features

- Uses OpenAI GPT-4o-mini for conversational AI
- Extracts profile information from `resume.pdf`
- Records user interest and unanswered questions via Pushover notifications
- Professional, engaging responses tailored for potential clients or employers

## Setup

1. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

2. **Set up environment variables:**
   ```sh
   export PUSHOVER_TOKEN=your_token
   export PUSHOVER_USER=your_user_key
   export OPENAI_API_KEY=your_openai_key
   ```
3. **Add Your Resume:**

Place your PDF resume as resume.pdf in the project directory
Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
