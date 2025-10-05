# API Documentation: Create AI-Ready Vector Datasets for LLMs with Bright Data, Gemini & Pinecone

## Overview
Automated workflow: Create AI-Ready Vector Datasets for LLMs with Bright Data, Gemini & Pinecone. This workflow integrates 14 different services: stickyNote, vectorStorePinecone, embeddingsGoogleGemini, httpRequest, textSplitterRecursiveCharacterTextSplitter. It contains 31 nodes and follows best practices for error handling and security.

## Workflow Metadata
- **Total Nodes**: 48
- **Complexity Level**: Complex
- **Estimated Execution Time**: 30+ seconds
- **Error Handling**: ✅ Implemented

## Trigger Information
### Trigger Types
- `n8n-nodes-base.manualTrigger`

## Node Types Used
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.stickyNote`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `@n8n/n8n-nodes-langchain.embeddingsGoogleGemini`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `@n8n/n8n-nodes-langchain.chainLlm`
- `n8n-nodes-base.httpRequest`
- `@n8n/n8n-nodes-langchain.vectorStorePinecone`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `@n8n/n8n-nodes-langchain.agent`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stopAndError`
- `@n8n/n8n-nodes-langchain.informationExtractor`

## Integrations
- Google
- Google
- Google
- Google

## Required Credentials
- `googlePalmApi`
- `httpHeaderAuth`
- `pineconeApi`

## Environment Variables
- `WEBHOOK_URL`
- `BASE_URL`
- `API_BASE_URL`
