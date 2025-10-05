# API Documentation: PUQ Docker NextCloud deploy

## Overview
Automated workflow: PUQ Docker NextCloud deploy. This workflow integrates 10 different services: webhook, stickyNote, httpRequest, code, switch. It contains 56 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 85
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.webhook`
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.respondToWebhook`

### Webhook Endpoints
- **Path**: `docker-nextcloud`
- **Method**: `['POST']`
- **Webhook ID**: `4e8168b3-2cad-462a-9750-152986331ce2`


## Node Types Used
- `n8n-nodes-base.webhook`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.respondToWebhook`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.code`
- `n8n-nodes-base.switch`
- `n8n-nodes-base.ssh`
- `n8n-nodes-base.set`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `httpBasicAuth`
- `sshPassword`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
