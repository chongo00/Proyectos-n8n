# API Documentation: Stickynote Workflow

## Overview
Automated workflow: Stickynote Workflow. This workflow integrates 8 different services: textClassifier, stickyNote, gmailTrigger, agent, stopAndError. It contains 13 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 18
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.gmailTrigger`

## Node Types Used
- `@n8n/n8n-nodes-langchain.textClassifier`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.googleCalendarTool`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.stopAndError`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.gmailTrigger`

## Integrations
- Google

## Required Credentials
- `openAiApi`
- `googleCalendarOAuth2Api`
- `gmailOAuth2`

## Environment Variables
- No environment variables required
