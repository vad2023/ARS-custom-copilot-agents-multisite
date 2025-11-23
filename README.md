# ARS Custom Copilot Agents (Multi-Site)

This repository contains a reference implementation for multi-site, Copilot-style
agentic routing across SharePoint-backed knowledge bases using Azure OpenAI.

It assumes you already have site-specific RAG indexes (e.g., from the
`azure-openai-sharepoint-rag-demo` project) and focuses on:

- Defining `SiteAgent` objects
- Routing user questions to the right knowledge base(s)
- Merging context across sites and generating a final answer
