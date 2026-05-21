# Zoho-lead-automation
# 🚀 Zoho CRM Lead Management & Automation System

A fully automated lead management platform built using Zoho Creator and Deluge scripting to streamline client intake, workflow automation, and sales pipeline tracking.

---

## 📌 Project Overview

This system was built to simulate a real-world CRM automation solution for a property development company. It handles the complete lead lifecycle — from initial intake to priority assignment, task creation, and email notification — without any manual intervention.

---

## ✅ Features

- **Automated Lead Intake** — Custom form captures lead data including name, company, industry, and budget
- **Auto Priority Assignment** — Deluge script automatically assigns High/Medium/Low priority based on budget value
- **Auto Status Classification** — Leads are classified as Hot Lead, Warm Lead, or Cold Lead instantly on submission
- **Welcome Email Notification** — Automated email sent to team on every new lead submission
- **Auto Task Creation** — Follow-up task automatically generated for every new lead with 3-day due date
- **KPI Dashboard** — Real-time metrics including Total Leads, Closed Won, Closed Lost, and pipeline funnel
- **Sales Pipeline View** — Kanban board tracking leads across Qualification, Proposal, Negotiation stages

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Zoho Creator | Low-code app builder and form management |
| Deluge Scripting | Workflow automation and business logic |
| Zoho CRM | Lead and pipeline management |
| REST APIs | Data synchronization |

---

## ⚙️ Automation Logic

### Auto Priority Assignment
if Budget >= 50,000 → Priority = High, Status = Hot Lead
if Budget >= 20,000 → Priority = Medium, Status = Warm Lead
else → Priority = Low, Status = Cold Lead

### Auto Task Creation
- Triggered on every new lead submission
- Creates a follow-up task with lead name and priority
- Due date automatically set to 3 days from submission

### Welcome Email
- Triggered on successful form submission
- Sends notification email with full lead details

---

## 📊 Dashboard KPIs

- Total Leads
- Closed Won
- Closed Lost  
- Pipeline Funnel by Stage
- Interaction Type Distribution

---

## 🗂️ Forms Built

- **Leads** — Main lead intake form with 9 fields
- **Tasks** — Auto-generated follow-up task tracker

---

## 📁 Project Structure
zoho-lead-automation/
├── README.md
├── screenshots/
│   ├── dashboard.png
│   ├── leads-report.png
│   ├── tasks.png
│   └── lead-record.png
├── deluge-scripts/
│   ├── auto-priority-assignment.ds
│   └── auto-task-creation.ds

---

## 🔮 Future Improvements

- Integrate with WhatsApp API for instant lead notifications
- Add Zoho Analytics for advanced reporting
- Connect to Zoho CRM for enterprise pipeline management
- Build public-facing lead capture portal

---

## 👤 Author

**Syed Fahad Ehsan**  
AI & Data Science Student — Middlesex University Dubai  
fahadehsansyed@gmail.com
