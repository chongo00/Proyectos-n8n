# API Documentation: Multi-Agent Conversation

## Overview
Automated workflow: Multi-Agent Conversation. This workflow integrates 9 different services: stickyNote, code, agent, set, memoryBufferWindow. It contains 18 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 23
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ❌ Not implemented

## Trigger Information
### Trigger Types
- `@n8n/n8n-nodes-langchain.chatTrigger`

## Node Types Used
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.lmChatOpenRouter`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `n8n-nodes-base.code`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`

## Integrations
- No external integrations detected

## Required Credentials
- `openRouterApi`

## Environment Variables
- No environment variables required
