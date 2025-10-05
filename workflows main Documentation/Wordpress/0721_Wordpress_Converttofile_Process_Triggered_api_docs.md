# API Documentation: Manualtrigger Workflow

## Overview
Automated workflow: Manualtrigger Workflow. This workflow integrates 7 different services: convertToFile, wordpress, stickyNote, googleDrive, set. It contains 9 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 14
- **Complexity Level**: Moderate
- **Estimated Execution Time**: 5-30 seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.wordpress`
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.googleDrive`
- `n8n-nodes-base.convertToFile`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google

## Required Credentials
- `googleApi`
- `wordpressApi`

## Environment Variables
- `WEBHOOK_URL`
