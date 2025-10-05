# API Documentation: Localfiletrigger Workflow

## Overview
Automated workflow: Localfiletrigger Workflow. This workflow integrates 12 different services: stickyNote, code, agent, readWriteFile, splitOut. It contains 21 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 26
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.localFileTrigger`

## Node Types Used
- `n8n-nodes-base.extractFromFile`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.toolCode`
- `n8n-nodes-base.localFileTrigger`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.code`
- `n8n-nodes-base.readWriteFile`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `openAiApi`

## Environment Variables
- No environment variables required
