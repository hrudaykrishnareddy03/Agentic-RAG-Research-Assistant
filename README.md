## ResearchPilot AI – Agentic RAG Research Assistant

ResearchPilot AI is an AI-powered research assistant built using Python, LangChain, Google Gemini, and Retrieval-Augmented Generation (RAG). It allows users to retrieve relevant information from PDF documents and generate context-aware responses to natural language queries.

The project uses an example PDF to demonstrate document loading, text chunking, semantic embedding, and similarity-based retrieval using Hugging Face embeddings and ChromaDB. The system can be adapted to work with other PDF documents, enabling users to query document-specific information. It also integrates Tavily web search to retrieve relevant information from external web sources, combining document retrieval and web search for more informative responses.

### Key Features
- **PDF Document Processing:** Load and process PDF files for information retrieval.
- **Retrieval-Augmented Generation (RAG):** Retrieve relevant document content to support AI-generated responses.
- **Semantic Search:** Generate text embeddings using Hugging Face and store them in ChromaDB.
- **Agentic AI:** Use LangChain tools to coordinate document retrieval and web search.
- **Web Search Integration:** Use Tavily to retrieve information from external sources.
- **Natural Language Question Answering:** Ask questions in plain English and receive context-aware answers.

### Tech Stack
Python, LangChain, Google Gemini, Retrieval-Augmented Generation (RAG), ChromaDB, Hugging Face Embeddings, Tavily Search, PyPDF.

### Use Cases
- Querying PDF documents and extracting relevant information.
- Research assistance and knowledge retrieval.
- Document-based question answering.
- Combining information from uploaded documents with web search results.
