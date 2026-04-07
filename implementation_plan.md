# Implementation Plan - README.md Improvement

The goal is to update `README.md` to reflect only the actual components and features present in the `Graph_RAG` project.

## Current Project Components
- **Language**: Python (v3.11+)
- **Dependency Management**: Poetry
- **Database**: Neo4j (Graph Database)
- **AI Models**: GPT-4o (via LangChain & OpenAI)
- **UI**: Streamlit
- **Core Modules**:
  - `graph_rag/app.py`: Streamlit entry point, manages UI and graph population.
  - `graph_rag/graph.py`: Handles graph construction from YouTube, Wikipedia, and Text.
  - `graph_rag/rag.py`: Implements hybrid RAG (Vector + Cypher).
  - `graph_rag/entities.py`: Pydantic models for entity extraction.

## Changes to README.md
1. **Header & Visuals**: Keep existing images as they are present in `graph_rag/images`.
2. **Project Overview**: Focus on YouTube/Wikipedia/Text extraction and Hybrid retrieval.
3. **Core Features**: List specific capabilities confirmed in the code.
4. **Project Structure**: Add a brief section showing the file structure.
5. **Setup Instructions**:
    - Update Neo4j Docker instructions.
    - Keep Poetry instructions.
    - Ensure the run command points correctly to `streamlit run graph_rag/app.py`.

## Verification
- Double-check all file paths and dependency names match `pyproject.toml` and the filesystem.
