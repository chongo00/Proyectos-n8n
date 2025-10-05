# API Documentation: Summarize Glassdoor Company Info with Google Gemini and Bright Data Web Scraper

## Overview
Automated workflow: Summarize Glassdoor Company Info with Google Gemini and Bright Data Web Scraper. This workflow integrates 11 different services: stickyNote, httpRequest, wait, textSplitterRecursiveCharacterTextSplitter, lmChatGoogleGemini. It contains 23 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 44
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `n8n-nodes-base.httpRequest`
- `@n8n/n8n-nodes-langchain.chainSummarization`
- `n8n-nodes-base.stopAndError`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`
- `n8n-nodes-base.wait`

## Integrations
- Google

## Required Credentials
- `googlePalmApi`
- `httpHeaderAuth`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
- `API_BASE_URL`
