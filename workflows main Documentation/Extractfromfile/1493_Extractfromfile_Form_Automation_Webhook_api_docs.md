# API Documentation: Extractfromfile Workflow

## Overview
Automated workflow: Extractfromfile Workflow. This workflow integrates 11 different services: textClassifier, stickyNote, formTrigger, httpRequest, airtable. It contains 28 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 37
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.formTrigger`

## Node Types Used
- `n8n-nodes-base.extractFromFile`
- `n8n-nodes-base.airtable`
- `@n8n/n8n-nodes-langchain.textClassifier`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.form`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.formTrigger`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `openAiApi`
- `airtableTokenApi`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
