# Langchain with RAG
This project uses a Langchain, Chromadb, NLP techniques and embeddings for intelligent retrieval. 
Data is Processed multiple document formats (.docx, .pdf, .txt) using Python-based custom loaders
text is splitted into manageable chunks with LangChain's Recursive Character TextSplitter.
Embedded the text using the sentence-transformers/all-MiniLM-L6-v2 model and stored it in ChromaDB.
Implemented a similarity search function that efficiently retrieves relevant document chunks based on a query. 
This system supports efficient, scalable semantic search across diverse document types.
