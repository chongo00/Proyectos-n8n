# API Documentation: Form Workflow

## Overview
Automated workflow: Form Workflow. This workflow integrates 6 different services: stickyNote, formTrigger, stopAndError, slack, googleSheets. It contains 15 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 20
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.formTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.googleSheets`
- `n8n-nodes-base.form`
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google
- Google
- Slack

## Required Credentials
- `googleSheetsOAuth2Api`
- `slackApi`

## Environment Variables
- `WEBHOOK_URL`
