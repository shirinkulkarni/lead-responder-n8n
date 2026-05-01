# Instant Lead Capture + Follow-Up Bot

A fully automated workflow that captures leads from a website form, stores them in Google Sheets, sends a follow-up email after a delay, and instantly notifies the business owner.

Built using n8n as part of an AI automation portfolio project.

---

##  Overview

Many small businesses lose potential customers because they don’t follow up quickly enough.

This workflow solves that problem by automating the entire lead management process — from capture to follow-up.

---

##  Features

- Capture leads via webhook (website form)
- Store leads automatically in Google Sheets
- Send delayed follow-up email to the lead
- Notify business owner instantly
- Fully automated — no manual work required

---

##  Workflow Logic

### Step 1 — Lead Submission
A customer fills a form on the website.

Webhook receives:
- Name
- Phone
- Email
- Interest

### Step 2 — Store Lead
Lead data is automatically saved in Google Sheets.

### Step 3 — Wait Period
Workflow waits 1 hour before follow-up.

### Step 4 — Send Follow-Up Email
Lead receives:
- Thank-you message
- Product catalogue / link
- Invitation to book a trial or meeting

### Step 5 — Notify Business Owner
Business owner gets instant email notification of new lead.

---

##  Tech Stack

- n8n (Workflow Automation)
- Google Sheets API
- Gmail API
- Webhooks

---

## 📂 Workflow Architecture
