# 📄 AI Resume Screening System

An AI-powered recruitment automation workflow built using **n8n**, **Google Gemini**, **PDF Processing**, **Airtable**, **Gmail**, and **Slack**.

The workflow automatically extracts resume information, evaluates candidates, scores them, stores candidate information, and assists HR with recruitment.

---

## Features

- Resume PDF processing
- AI resume analysis
- Candidate scoring
- Skill extraction
- Experience extraction
- Education extraction
- AI recommendations
- Airtable candidate database
- Interview invitation emails
- HR Slack notifications

---

## Tech Stack

- n8n
- Google Gemini
- PDF Extract
- Airtable
- Gmail
- Slack

---

## Workflow

Candidate uploads resume
→ Extract PDF text
→ Gemini analyzes resume
→ Parse JSON
→ Candidate scoring
→ Store in Airtable

If score ≥ 80
    → Interview Email
    → Slack Notification

Else
    → Rejection Email

---

## Business Value

Automates repetitive HR screening tasks and helps recruiters identify strong candidates more efficiently.

---

## Screenshots

### Workflow

![Workflow][screenshots/workflow.png]
### Resume Upload Form

![Form][screenshots/form.png]

### Airtable

![Airtable][screenshots/airtable.png

### Slack

![Slack][screenshots/slack.png]

### Gmail

![Gmail][screenshots/gmail.png]

---

## Future Improvements

- Multiple resume ranking
- ATS integration
- Automatic interview scheduling
- Resume similarity search
- AI-generated interview questions

---

## Author

Ayman Amjad
