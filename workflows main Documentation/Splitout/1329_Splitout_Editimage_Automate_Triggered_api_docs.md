# API Documentation: Manualtrigger Workflow

## Overview
Automated workflow: Manualtrigger Workflow. This workflow integrates 10 different services: stickyNote, lmChatGoogleGemini, splitOut, chainLlm, outputParserStructured. It contains 13 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 18
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.googleDrive`
- `n8n-nodes-base.editImage`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`

## Integrations
- Google
- Google

## Required Credentials
- `googleDriveOAuth2Api`
- `googlePalmApi`

## Environment Variables
- No environment variables required
