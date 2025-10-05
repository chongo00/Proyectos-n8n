# API Documentation: Stickynote Workflow

## Overview
Automated workflow: Stickynote Workflow. This workflow integrates 8 different services: stickyNote, toolHttpRequest, agent, stopAndError, toolWikipedia. It contains 12 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 21
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `@n8n/n8n-nodes-langchain.manualChatTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.manualChatTrigger`
- `@n8n/n8n-nodes-langchain.lmChatOllama`
- `@n8n/n8n-nodes-langchain.toolHttpRequest`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.stopAndError`
- `@n8n/n8n-nodes-langchain.toolWikipedia`

## Integrations
- No external integrations detected

## Required Credentials
- `ollamaApi`

## Environment Variables
- `API_BASE_URL`
