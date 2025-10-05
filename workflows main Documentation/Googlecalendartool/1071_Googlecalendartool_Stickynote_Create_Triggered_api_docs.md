# API Documentation: Build an MCP Server with Google Calendar

## Overview
Automated workflow: Build an MCP Server with Google Calendar. This workflow integrates 9 different services: stickyNote, agent, mcpClientTool, mcpTrigger, stopAndError. It contains 28 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 33
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `@n8n/n8n-nodes-langchain.mcpTrigger`
- `@n8n/n8n-nodes-langchain.chatTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.mcpClientTool`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `n8n-nodes-base.googleCalendarTool`
- `@n8n/n8n-nodes-langchain.mcpTrigger`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google
- Google
- Google
- Google

## Required Credentials
- `openAiApi`
- `googleCalendarOAuth2Api`

## Environment Variables
- `WEBHOOK_URL`
