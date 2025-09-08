# RAG_LLM_pipeline

# RAG Pipeline Project

## Project Overview
This project demonstrates the creation of a **Retrieval-Augmented Generation (RAG)** pipeline. The pipeline loads information from a specified URL, processes it, and makes it accessible for a **question-and-answer application**. This project is part of a hands-on curriculum covering both foundational and advanced concepts in Generative AI.


## Key Technologies & Learning Outcomes

| Technology | What I Learned & Why I Used It |
|------------|--------------------------------|
| **LangChain** | Learned how to build an end-to-end RAG pipeline, from document loading to setting up a Q&A chain. Used to orchestrate components like document loaders, text splitters, and vector storage. |
| **ChromaDB** | Learned to store and manage document chunks in an open-source vector database. Crucial for efficient retrieval based on user queries. Chosen for its ease of use and local deployment. |
| **Hugging Face Embeddings** | Used the `sentence-transformers/all-MiniLM-L6-v2` model to generate vector embeddings for text chunks. Essential for converting text into a numerical format for similarity searches. Chosen for its popularity and effectiveness as an open-source alternative. |
| **Falcon& Python** | Integrated with the Falcon to power the LLM component of the RAG pipeline. Python was used to script the entire workflow, making the process modular and scalable. |


## Concepts Covered

- **Document Loading**: Extract content from web pages using `WebBaseLoader`.
- **Text Splitting**: Break large documents into smaller chunks with `RecursiveCharacterTextSplitter` for effective retrieval.
- **Vector Embeddings & Vector Stores**: Convert text into searchable numerical formats and store/retrieve embeddings using a vector database.
- **RAG Pipeline**: Build a functional RAG pipeline to enhance LLM knowledge with external data.
- **LangChain Components**: Gain hands-on experience with prompts, chains, and agents.
