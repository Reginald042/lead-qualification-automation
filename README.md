Lead Qualification Automation
Automated Lead Qualificationa and notififcation workflow built with n8n, Slack, Gmail, and Google Sheets.
## Overview

This workflow automatically identifies high-priority leads based on pricing-related inquiries and routes them for immediate attention.

When a lead submits a form, the workflow analyzes the inquiry, notifies the sales team, sends an automated response, and logs the lead information for tracking.

##Tech Stack

- n8n
- Webhooks
- Slack
- Google Sheets
- IF Logic

  ## Workflow Logic
  A lead submits an inquiry through a form.
The workflow analyzes the inquiry for pricing-related keywords.
High-priority leads are identified using IF logic.
High-priority leads trigger:
A Slack notification to the sales team to take action immediately
An automated email response to the lead
Logging into Google Sheets
Non-priority leads bypass notifications and email responses and are logged into Google Sheets for later review.

## Business impact
Reduces manual lead qualification efforts
Improves response times for high-intent prospects
Ensures urgent sales inquiries receive immediate attention
Prevents low-priority leads from being overlooked
Centralizes lead tracking and record keeping in Google Sheets
Improves team visibility through automated Slack notifications
