Installations done in this project:

chromadb                                 1.3.5
lancedb                                  0.25.3
langchain                                0.3.27
langchain-community                      0.3.31
langchain-core                           0.3.80
langchain-openai                         0.3.35
langchain-text-splitters                 0.3.9
openai                                   2.7.1
pandas                                   2.2.3
pydantic                                 2.12.4
pydantic_core                            2.41.5
pydantic-settings                        2.11.0


PERSONALIZED REAL ESTATE AGENT: HOMEMATCH
------------------------------------------

This is an AI-agent which helps in finding the best suited options regarding properties in various locations for buyers. 

Steps for building personalized real estate agent:

1. Generation synthetic data for real estate listings using LLM (gpt-3.5)
2. Splitting the document into chunks.
3. Conversion chunks into embeddings.
4. Creation of LanceDB vector database and converting the embeddings into the database.
5. Performing semantic search on listings based on Buyer's preference.
6. Using RAG to retrieve information from vector database and performing search and augmenting on listing descriptions
7. Building a Chatbot
