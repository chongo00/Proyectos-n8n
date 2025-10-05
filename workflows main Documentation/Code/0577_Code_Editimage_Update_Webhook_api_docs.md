# API Documentation: Manualtrigger Workflow

## Overview
Automated workflow: Manualtrigger Workflow. This workflow integrates 10 different services: stickyNote, httpRequest, code, lmChatGoogleGemini, chainLlm. It contains 19 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 28
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.merge`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.code`
- `n8n-nodes-base.editImage`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google

## Required Credentials
- `googlePalmApi`

## Environment Variables
- `WEBHOOK_URL`
