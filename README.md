# Hybrid Retrieval for RAG

## Overview  
This project demonstrates a hybrid retrieval approach for Retrieval-Augmented Generation (RAG) applications. It combines vector search (using embeddings) and graph search (Neo4j) to retrieve context from both unstructured and structured data. The context is then passed to LLMs (Ollama, Gemini API) to generate responses.

## Setup  
1. Set up and run a Neo4j database instance.  
2. Configure the Ollama and Gemini API credentials.  
3. Run the Jupyter Notebook to perform the retrieval and LLM integration.

## Key Components  
- **Vector Retrieval**: Retrieves unstructured context using embeddings.  
- **Graph Retrieval**: Extracts relevant entities and context from a Neo4j knowledge graph.  
- **Hybrid Retrieval**: Combines results from vector and graph searches, which are then passed to an LLM for response generation.

## Usage  
Execute the Jupyter Notebook to explore the hybrid retrieval process and see how it integrates with the LLMs.

