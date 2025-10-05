# API Documentation: Extract And Decode Google News RSS URLs to Clean Article Links

## Overview
Automated workflow: Extract And Decode Google News RSS URLs to Clean Article Links. This workflow integrates 10 different services: stickyNote, httpRequest, code, set, stopAndError. It contains 24 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 37
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.rssFeedRead`
- `n8n-nodes-base.limit`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.code`
- `n8n-nodes-base.html`
- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- No credentials required

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
