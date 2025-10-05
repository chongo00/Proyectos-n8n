# API Documentation: Set Workflow

## Overview
Automated workflow: Set Workflow. This workflow integrates 14 different services: webhook, stickyNote, httpRequest, switch, respondToWebhook. It contains 43 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 68
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.webhook`
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.respondToWebhook`

### Webhook Endpoints
- **Path**: `e03c7d39-1dce-4ac5-8db8-2b4511a85a07`
- **Method**: `POST`
- **Webhook ID**: `e03c7d39-1dce-4ac5-8db8-2b4511a85a07`


## Node Types Used
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.summarize`
- `n8n-nodes-base.webhook`
- `n8n-nodes-base.sort`
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.limit`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.switch`
- `n8n-nodes-base.serviceNow`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- Slack
- Slack
- Slack
- Slack

## Required Credentials
- `slackApi`
- `serviceNowBasicApi`

## Environment Variables
- `API_BASE_URL`
