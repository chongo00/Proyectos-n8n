# API Documentation: Manualtrigger Workflow

## Overview
Automated workflow: Manualtrigger Workflow. This workflow integrates 13 different services: stickyNote, textSplitterRecursiveCharacterTextSplitter, code, agent, splitOut. It contains 21 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 26
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.gmail`
- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `n8n-nodes-base.splitOut`
- `@n8n/n8n-nodes-langchain.chainSummarization`
- `@n8n/n8n-nodes-langchain.informationExtractor`
- `n8n-nodes-base.code`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `n8n-nodes-base.stopAndError`
- `@n8n/n8n-nodes-langchain.toolWikipedia`

## Integrations
- No external integrations detected

## Required Credentials
- `openAiApi`
- `gmailOAuth2`

## Environment Variables
- No environment variables required
