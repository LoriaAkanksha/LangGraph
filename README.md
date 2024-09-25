# LangGraph

The chatbot utilizes a hybrid approach to knowledge retrieval by integrating a generative AI model to retrieve data from custom data and external data sources like Wikipedia.​It routes user queries either to a RAG-based retrieval process or performs a Wikipedia search to return the most relevant results.


**LangGraph** manages and routes the flow of states for document retrieval. It allows conditional edges for dynamic question routing.​
**LangServe** integrates the workflow with FastAPI, managing routing and providing endpoints for interaction.​
**LangChain** is used for document handling, embedding, semantic search, and retrieval using a vector database.​
**FastAPI** provides the backend API for interacting with the chatbot.​
**Streamlit** is used for the frontend UI to provide an interactive interface for users to query the chatbot.


