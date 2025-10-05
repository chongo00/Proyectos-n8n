# API Documentation: Gmailtrigger Workflow

## Overview
Automated workflow: Gmailtrigger Workflow. This workflow integrates 8 different services: stickyNote, wait, gmailTrigger, gmailTool, agent. It contains 14 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 19
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.gmailTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `n8n-nodes-base.gmailTool`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.stopAndError`
- `n8n-nodes-base.wait`
- `n8n-nodes-base.gmailTrigger`

## Integrations
- No external integrations detected

## Required Credentials
- `openAiApi`
- `gmailOAuth2`

## Environment Variables
- No environment variables required
