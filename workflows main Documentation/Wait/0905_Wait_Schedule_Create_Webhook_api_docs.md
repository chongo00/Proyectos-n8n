# API Documentation: Scheduletrigger Workflow

## Overview
Automated workflow: Scheduletrigger Workflow. This workflow integrates 11 different services: stickyNote, httpRequest, facebookGraphApi, wait, scheduleTrigger. It contains 37 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 54
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.facebookGraphApi`
- `n8n-nodes-base.googleSheets`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.scheduleTrigger`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`
- `n8n-nodes-base.wait`

## Integrations
- Google
- Google
- Google
- Google
- Google

## Required Credentials
- `googleSheetsOAuth2Api`
- `googlePalmApi`
- `httpHeaderAuth`
- `facebookGraphApi`

## Environment Variables
- `WEBHOOK_URL`
- `API_BASE_URL`
