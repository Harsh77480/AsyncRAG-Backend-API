# AsyncRAG-Backend-API

## Overview
This project integrates Langchain with FastAPI, providing a framework for document indexing and retrieval, as well as chat functionality, using PostgreSQL and pgvector. It is designed to support both synchronous and asynchronous operations.

## Features
- **Document Management**: Methods for adding, retrieving, and deleting documents.
- **Vector Store**: Utilizes Langchain's vector store for efficient document retrieval.
- **Chat Functionality**: Includes a chat endpoint that leverages Langchain for response generation.
- **Asynchronous Support**: Offers async operations for enhanced performance.

## Configuration
Ensure to set environment variables such as `POSTGRES_DB`, `POSTGRES_USER`, `POSTGRES_PASSWORD`, `DB_HOST`, `DB_PORT`, and `OPENAI_API_KEY`. Configure the database connection string appropriately and initialize Langchain and OpenAI embeddings according to project needs.
