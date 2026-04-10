#  Google Form → ClickUp Automation Pipeline
**Author: Maria Khan** | AI Engineer & Automation Developer

##  Project Overview
An end-to-end business automation workflow built with n8n that 
eliminates manual data entry by connecting 4 tools automatically.

## ⚡ What It Does
When a user submits a Google Form:
1. Data is saved in Google Sheets automatically
2. A task is created in ClickUp via API
3. A personalized confirmation email is sent via Gmail

##  Tools Used
- **n8n** — Workflow automation
- **Google Forms & Sheets** — Data capture & storage
- **ClickUp API** — Task management
- **Gmail** — Email confirmation
- **Webhooks & Triggers** — Event-based automation

##  Files
- `workflow.json` — Import this into n8n to run the workflow
- `README.md` — Project documentation

##  How to Use
1. Import `workflow.json` into your n8n instance
2. Connect Google, ClickUp, and Gmail credentials
3. Set your ClickUp List ID
4. Activate the workflow — done!

## Key Concepts Demonstrated
- API integration (ClickUp REST API)
- Webhook triggers
- Multi-step workflow automation
- Dynamic data mapping between apps
  ## 📸 Workflow Preview
![Workflow](images/workflow-screenshot.png)
