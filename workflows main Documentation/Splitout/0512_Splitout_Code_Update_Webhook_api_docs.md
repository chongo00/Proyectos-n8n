# API Documentation: Httprequest Workflow

## Overview
Automated workflow: Httprequest Workflow. This workflow integrates 11 different services: stickyNote, httpRequest, code, splitOut, n8n. It contains 17 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 26
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
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.code`
- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.n8n`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `n8nApi`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
