# API Documentation: SearchApi Youtube Video Summary

## Overview
Automated workflow: SearchApi Youtube Video Summary. This workflow integrates 9 different services: stickyNote, searchApi, textSplitterRecursiveCharacterTextSplitter, splitOut, summarize. It contains 12 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 17
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.summarize`
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `@searchapi/n8n-nodes-searchapi.searchApi`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `n8n-nodes-base.splitOut`
- `@n8n/n8n-nodes-langchain.chainSummarization`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- No credentials required

## Environment Variables
- No environment variables required
