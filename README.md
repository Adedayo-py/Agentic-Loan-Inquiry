# Agentic-Loan-Inquiry
Create a RAG-enabled WhatsApp Loan Inquiry Agent in Google Colab.
To achieve this, perform the following steps:
Secure API Key Setup: Demonstrate how to retrieve the OpenAI API Key securely using google.colab.userdata to avoid hardcoding secrets.
Install Dependencies: Install necessary packages including openai, flask, pyngrok, and chromadb.
Infuse RAG Concept: Build a step-by-step beginner guide and Python code using a simple vector store (like ChromaDB) to store, search, and retrieve policy documents for the loan agent.
Build the Loan Inquiry Agent: Program the core AI agent using the OpenAI API, configuring it with system prompts that utilize the retrieved RAG contexts.
Test Agent Responses Locally: Implement an interactive local CLI loop to verify the agent's accuracy and behavior using the retrieved context.
Set Up Webhook for WhatsApp: Write a Flask application that receives Twilio WhatsApp webhook payloads, processes them through the RAG loan agent, and formats the response.
Expose Webhook and Deploy Guide: Use pyngrok to expose the local Flask server to a public URL, and write a clear, step-by-step guide on how to configure this URL in the Twilio Sandbox for WhatsApp.
