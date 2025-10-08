This is a college information chatbot built using RAG (Retrieval-Augmented Generation). 
-It answers questions related to college rules, fees, hostel, library, and other facilities. 
-The system loads text documents from a zip file, splits them into chunks, generates embeddings using a transformer model, and stores them in a vector database. When a user asks a question, it retrieves the most relevant document chunks and uses a language model to generate a concise answer based only on the retrieved context.
