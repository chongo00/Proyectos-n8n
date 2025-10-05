# API Documentation: Backup n8n Workflows to Bitbucket

## Overview
Automated workflow: Backup n8n Workflows to Bitbucket. This workflow processes data and performs automated tasks.

## Workflow Metadata
- **Total Nodes**: 27
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.if`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.stopAndError`
- `n8n-nodes-base.code`
- `n8n-nodes-base.set`
- `n8n-nodes-base.n8n`
- `n8n-nodes-base.wait`

## Integrations
- No external integrations detected

## Required Credentials
- `httpBasicAuth`
- `n8nApi`

## Environment Variables
- `BASE_URL`
