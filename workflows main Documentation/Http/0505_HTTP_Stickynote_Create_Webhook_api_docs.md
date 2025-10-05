# API Documentation: Httprequest Workflow

## Overview
Automated workflow: Httprequest Workflow. This workflow integrates 6 different services: stickyNote, httpRequest, stopAndError, sendInBlue, if. It contains 34 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 63
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.executeWorkflowTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.sendInBlue`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.executeWorkflowTrigger`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- No credentials required

## Environment Variables
- `BASE_URL`
- `API_BASE_URL`
