# API Documentation: Blog Automation TEMPLATE

## Overview
Automated workflow: Blog Automation TEMPLATE. This workflow integrates 11 different services: stickyNote, httpRequest, code, scheduleTrigger, chainLlm. It contains 44 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 53
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.googleSheets`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.code`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google
- Google
- Google
- Google
- Google
- Google

## Required Credentials
- `googleSheetsOAuth2Api`
- `openAiApi`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
