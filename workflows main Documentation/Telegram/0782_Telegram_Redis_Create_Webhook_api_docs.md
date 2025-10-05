# API Documentation: Telegramtrigger Workflow

## Overview
Automated workflow: Telegramtrigger Workflow. This workflow integrates 16 different services: textClassifier, telegramTrigger, httpRequest, stickyNote, telegram. It contains 56 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 69
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.telegramTrigger`

## Node Types Used
- `n8n-nodes-base.telegram`
- `@n8n/n8n-nodes-langchain.textClassifier`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.googleSheets`
- `@n8n/n8n-nodes-langchain.memoryRedisChat`
- `n8n-nodes-base.executionData`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.set`
- `n8n-nodes-base.switch`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.memoryManager`
- `n8n-nodes-base.redis`
- `n8n-nodes-base.telegramTrigger`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google
- Google
- Google
- Google

## Required Credentials
- `openAiApi`
- `googleSheetsOAuth2Api`
- `telegramApi`
- `redis`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
