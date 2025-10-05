# API Documentation: Stickynote Workflow

## Overview
Automated workflow: Stickynote Workflow. This workflow integrates 11 different services: pipedrive, stickyNote, filter, httpRequest, clearbit. It contains 27 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 44
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.scheduleTrigger`

## Node Types Used
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.stopAndError`
- `n8n-nodes-base.filter`
- `n8n-nodes-base.set`
- `n8n-nodes-base.clearbit`
- `n8n-nodes-base.pipedrive`

## Integrations
- Slack

## Required Credentials
- `clearbitApi`
- `slackApi`
- `pipedriveApi`

## Environment Variables
- `BASE_URL`
- `API_BASE_URL`
