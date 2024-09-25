# LangGraph

The chatbot utilizes a hybrid approach to knowledge retrieval by integrating a generative AI model to retrieve data from custom data and external data sources like Wikipedia.​It routes user queries either to a RAG-based retrieval process or performs a Wikipedia search to return the most relevant results.


**LangGraph** manages and routes the flow of states for document retrieval. It allows conditional edges for dynamic question routing.​
**LangServe** integrates the workflow with FastAPI, managing routing and providing endpoints for interaction.​
**LangChain** is used for document handling, embedding, semantic search, and retrieval using a vector database.​
**FastAPI** provides the backend API for interacting with the chatbot.​
**Streamlit** is used for the frontend UI to provide an interactive interface for users to query the chatbot.


![image](https://github.com/user-attachments/assets/000d707b-791a-4977-8e7f-ef483b4435ac)


      
      
          ![image](https://github.com/user-attachments/assets/377a1ef9-5e39-40d5-9b6a-51849888996a)
