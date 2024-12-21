# Advanced Retrieval for AI with Chroma 🚀

**Information Retrieval (IR)** and **Retrieval Augmented Generation (RAG)** are only effective if the information retrieved from a database as a result of a query is relevant to the query and its application. 

However, challenges abound:  
- Queries often yield results that are **close in meaning** but fail to directly address the posed question.  
- Worse, irrelevant material can distract the **LLM** from finding the correct answers. 😓 

## Key Techniques for Enhanced Retrieval 🔑: 
1. **Query Expansion 🛠:**
   - Broaden user queries by including **related concepts and keywords** to enhance retrieval.  
   - Supercharge this traditional approach by leveraging an **LLM** to generate related terms or even suggest **possible answers** to include in the query. 
2. **Cross-Encoder Reranking 📊:**  
   - Refine retrieval by **reranking results** to surface the most relevant ones for the query. This method ensures that the results are prioritized and tailored to your needs.

3. **Training & Utilizing Embedding Adapters 🔄:**  
   - Adding an adapter layer to reshape embeddings emphasizes elements most relevant to specific applications, enhancing retrieval performance.

## Notebook List📚

| **Title**             | **Description**                                  | **Tecnology/Tools**                     | **Link**                   |
|-----------------------|--------------------------------------------------|-----------------------------------------|----------------------------|
| **Overview of Embeddings-Based Retrieval with ChromaDB** | Dive into the fundamentals of embeddings-based retrieval using ChromaDB. Explore how to store, query, and manage embeddings effectively, and build a simple Retrieval-Augmented Generation (RAG) system. | `ChromaDB`, `Embeddings`, `Retrieval-Augmented Generation (RAG)`, `OpenAI` | [Notebook](notebook/embeddings_based_retrieval_chromadb.ipynb) |
| **Pitfalls of Retrieval: When Simple Vector Search Fails** | Explore common challenges and limitations of simple vector search in embeddings-based retrieval. Understand scenarios where vector search may fail. | `Vector Search`, `Embeddings`, `Retrieval Systems`, `ChromaDB` | [Notebook](notebook/pitfalls_of_retrieval_vector_search_fails.ipynb) |
| **Query Expansion** | Enhance information retrieval by expanding user queries with related concepts and keywords using an LLM. Employ an LLM to suggest possible answers to queries and incorporate them into the query for improved retrieval performance. | `LLM`, `Information Retrieval`, `Query Expansion`, `Keyword Enrichment` | [Notebook](notebook/query_expansion_llm.ipynb) |
| **Cross-Encoder Reranking** | Improve retrieval results by reranking them using a cross-encoder to select the most relevant results based on the query. | `Cross-Encoder`, `Reranking`, `Information Retrieval`, `Query Optimization` | [Notebook](notebook/cross_encoder_reranking.ipynb) |
| **Training and Utilizing Embedding Adapters** | Add an adapter layer to reshape embeddings, improving retrieval by emphasizing elements that are relevant to your application. | `Embedding Adapters`, `Retrieval`, `Embedding Layers`, `Machine Learning` | [Notebook](notebook/embedding_adapters.ipynb) |

These strategies ensure more precise and effective retrieval, unlocking the full potential of Chroma for IR and RAG tasks! 🚀✨