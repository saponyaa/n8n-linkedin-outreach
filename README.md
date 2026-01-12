# LinkedIn Outreach Assistant (System 1)

This repository contains the n8n workflow for automating LinkedIn lead generation and personalized messages via WhatsApp.

## Files
- `linkedin_outreach_workflow.json` → Exported n8n workflow
- `screenshots/` → Example workflow screenshot and Google Sheet output

## Setup Instructions
1. Import `linkedin_outreach_workflow.json` into your n8n instance.
2. Configure credentials via the `/config` workflow (WhatsApp API, Google Sheets).
3. Test by sending `/outreach CEO marketing agencies USA` via WhatsApp.
4. Leads and messages will appear in the linked Google Sheet.

## Notes
- Current workflow uses mock AI output due to API quota limitations.
- System is ready for future integration with GrokAI or OpenAI.
