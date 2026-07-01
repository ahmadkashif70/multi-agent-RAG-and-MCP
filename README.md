# Agentic RAG and MCP Integration on Databricks

This repository contains two notebooks that demonstrate an end-to-end implementation of an agentic retrieval-augmented generation (RAG) system using Databricks, LangChain, LangGraph, and the Model Context Protocol (MCP).

## Project Overview

The project builds a knowledge base from a research PDF, applies different chunking and embedding strategies, and uses vector retrieval to ground LLM-generated responses. The system is then extended with MCP-based tool integration so an agent can retrieve context and answer questions in a more modular and extensible way.

## Included Notebooks

- agentic_rag_mcp_databricks.ipynb: Main implementation notebook covering document ingestion, chunking, embeddings, vector search, RAG orchestration, and MCP integration.
- agentic_rag_mcp_evaluation.ipynb: Evaluation notebook focused on agent behavior, tool usage, and response quality.

## Key Technologies

- Databricks
- Unity Catalog
- LangChain
- LangGraph
- Azure OpenAI
- Model Context Protocol (MCP)

## Summary

This project highlights experience with:
- Building retrieval-augmented generation systems
- Working with vector search and semantic retrieval
- Designing agent workflows with LangGraph
- Integrating tools through MCP servers
- Developing AI systems in a cloud-based data environment

## Next Steps

- Add a short architecture diagram
- Document setup steps and environment variables
- Push this repository to GitHub and include a link in your portfolio or resume
