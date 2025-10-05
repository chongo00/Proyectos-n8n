# API Documentation: Manualtrigger Workflow

## Overview
Automated workflow: Manualtrigger Workflow. This workflow integrates 10 different services: stickyNote, httpRequest, code, scheduleTrigger, merge. It contains 29 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 46
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.microsoftTeams`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.code`
- `n8n-nodes-base.set`
- `n8n-nodes-base.redis`
- `n8n-nodes-base.stopAndError`

## Integrations
- Microsoft

## Required Credentials
- `httpHeaderAuth`

## Environment Variables
- `BASE_URL`
- `API_BASE_URL`
