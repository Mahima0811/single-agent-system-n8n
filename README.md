# Single Agent System using n8n

## Project Overview
This project implements a Single Agent System using n8n to answer user queries through an AI-powered conversational workflow.

## Objective
To build an AI agent that accepts user questions, generates responses using a large language model, maintains conversational context, and uses a vector store to support document-based retrieval.

## Technologies Used
- n8n — workflow automation and agent orchestration
- Groq Chat Model — language model integration
- Simple Memory — conversational context
- Google Gemini Embeddings — text embeddings
- Simple Vector Store — vector-based document retrieval
- Google Drive — document source
- Default Data Loader — document loading

## Workflow
1. The user sends a message through the chat trigger.
2. The AI Agent processes the question.
3. The Groq Chat Model generates the response.
4. Simple Memory helps retain conversational context.
5. The vector-store components support document retrieval where configured.
6. The agent returns the response to the user.

## Example Use Case
The chatbot can answer questions about car loan eligibility criteria, credit scores, and other information available in its configured knowledge sources.

## Project Files
- `single-agent-system.json` — exported n8n workflow (to be added).

## Setup
1. Import the workflow JSON into your n8n instance.
2. Configure the required model, Google Drive, and embedding credentials.
3. Check that the vector store and document-loading connections are configured correctly.
4. Test the workflow using the chat trigger.

## Security
API keys, passwords, and private credentials must be configured securely in n8n and must not be committed to this repository.

## Notes
This repository documents an academic project. Actual responses depend on the configured model, credentials, and available knowledge sources.
