# API Documentation: Lmchatopenai Workflow

## Overview
Automated workflow: Lmchatopenai Workflow. This workflow integrates 8 different services: stickyNote, textSplitterRecursiveCharacterTextSplitter, telegram, scheduleTrigger, stopAndError. It contains 23 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 28
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.telegram`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `@n8n/n8n-nodes-langchain.openAi`
- `@n8n/n8n-nodes-langchain.chainSummarization`
- `n8n-nodes-base.scheduleTrigger`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `telegramApi`
- `openAiApi`

## Environment Variables
- No environment variables required
