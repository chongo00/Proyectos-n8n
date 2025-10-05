# API Documentation: Scans von PDF zu Nextcloud

## Overview
Automated workflow: Scans von PDF zu Nextcloud. This workflow integrates 5 different services: stickyNote, httpRequest, scheduleTrigger, stopAndError, nextCloud. It contains 9 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 22
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.nextCloud`
- `n8n-nodes-base.stopAndError`

## Integrations
- No external integrations detected

## Required Credentials
- `nextCloudApi`

## Environment Variables
- `BASE_URL`
- `API_BASE_URL`
