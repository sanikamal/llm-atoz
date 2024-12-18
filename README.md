# LLM AtoZ - Comprehensive Resource for Mastering Large Language Models 🚀

**LLM AtoZ** is a detailed repository designed to provide resources and guidance for mastering Large Language Models (LLMs). The repository offers code snippets, Jupyter notebooks, project examples, and industry best practices, catering to users ranging from beginners to advanced professionals. The materials cover prominent libraries, frameworks, and APIs within the natural language processing (NLP) field.

This repository features libraries such as `Hugging Face Transformers`, `LangChain`, `LlamaIndex`, `Unstructured` as well as `OpenAI`, `Cohere` `Gemini`. It is continuously updated to reflect the latest innovations and best practices in LLM development and deployment.

## Contents 📚

The repository is organized for easy navigation, featuring a detailed breakdown of each component, including the key tools and libraries, associated resources, and links to relevant documentation:

| **Title**             | **Description**                       | **Tecnology/Tools**                                  | **Link**                   |
|-----------------------|---------------------------------------|----------------------------------------------------|----------------------------|
| **LangChain: Models, Prompts, and Output Parsers** | Covers the use of models, prompts, and output parsers in LangChain. Focuses on calling LLMs, providing prompts, and parsing responses. | `LangChain`, `LLMs`, `Prompt Engineering`, `Output Parsing` | [Notebook](notebook/langchain_models_prompts_parsers.ipynb) |
| **LangChain: Memory** | Explores memory management for LLMs, including storing conversations and managing limited context space. Covers `ConversationBufferMemory`, `ConversationBufferWindowMemory`, `ConversationTokenBufferMemory`, and `ConversationSummaryMemory`. | `LangChain`, `LLMs`, `Memory Management` | [Notebook](notebook/langchain_memory.ipynb) |
| **LangChain: Chains** | Focuses on creating sequences of operations using Chains in LangChain. Includes `LLMChain`, `Sequential Chains` (`SimpleSequentialChain`, `SequentialChain`), and `Router Chain`. | `LangChain`, `LLMChain`, `SequentialChain`, `Router Chain` | [Notebook](notebook/langchain_chains.ipynb) |
| **LangChain: Q&A over Documents** | Demonstrates how to apply LLMs to proprietary data for question-answering tasks based on specific use case requirements. | `LangChain`, `LLMs`, `Q&A`, `Document Processing` | [Notebook](notebook/langchain_qa_over_documents.ipynb) |
| **LangChain: Evaluation** | Covers methods for evaluating LangChain applications, including example generation, manual evaluation and debugging, LLM-assisted evaluation, and the LangChain evaluation platform. | `LangChain`, `Evaluation`, `LLM`, `Debugging` | [Notebook](notebook/langchain_evaluation.ipynb) |
| **LangChain: Agents** | Explores the development of LLMs as reasoning agents. Covers using built-in LangChain tools like DuckDuckGo Search and Wikipedia, as well as defining custom tools. | `LangChain`, `LLM`, `Agents`, `Custom Tools` | [Notebook](notebook/langchain_agents.ipynb) |
| **Diving into Pinecone** | Explores the capabilities of Pinecone, focusing on essential operations such as inserting, updating, deleting, and querying vectors for fast, scalable AI-driven search and machine learning applications. | `Pinecone`, `Vector Database`, `AI Search`, `LLM` | [Notebook](notebook/diving_into_pinecone.ipynb) |
| **Jupyter AI** | A JupyterLab extension that provides an intuitive user interface for interacting with AI models. | `Jupyter AI`, `JupyterLab`, `AI Models` | [Notebook](notebook/jupyter_ai.ipynb) |
| **Guidelines for Prompting in ChatGPT** | Focuses on two key principles for writing effective prompts in ChatGPT: writing clear and specific instructions, and giving the model time to "think". Provides related tactics to optimize interaction with large language models. | `ChatGPT`, `Prompt Engineering`, `LLMs` | [Notebook](notebook/guidelines_for_prompting_chatgpt.ipynb) |
| **Iterative Prompt Development in ChatGPT** | Focuses on iteratively analyzing and refining prompts to generate marketing copy from a product fact sheet using ChatGPT. | `ChatGPT`, `Prompt Engineering`, `LLMs` | [Notebook](notebook/iterative_prompt_development_chatgpt.ipynb) |
| **Summarizing in ChatGPT** | Demonstrates how to summarize text with a focus on specific topics using ChatGPT, extracting the most relevant information based on user-defined criteria. | `ChatGPT`, `Summarization`, `LLMs`, `Topic-Focused Summarization` | [Notebook](notebook/summarizing_chatgpt.ipynb) |
| **Inferring in ChatGPT** | Demonstrates how to infer sentiment and extract topics from product reviews and news articles using ChatGPT. | `ChatGPT`, `Sentiment Analysis`, `Topic Extraction`, `LLMs` | [Notebook](notebook/inferring_chatgpt.ipynb) |
| **Transforming in ChatGPT** | Explores how to use ChatGPT for text transformation tasks such as language translation, spelling and grammar checking, tone adjustment, and format conversion. | `ChatGPT`, `Text Transformation`, `Language Translation`, `Spelling and Grammar Checking`, `LLMs` | [Notebook](notebook/transforming_chatgpt.ipynb) |
| **Expanding in ChatGPT** | Focuses on generating customer service emails tailored to individual customer reviews using ChatGPT. | `ChatGPT`, `Email Generation`, `Customer Service`, `LLMs` | [Notebook](notebook/expanding_chatgpt.ipynb) |
| **The Chat Format in ChatGPT** | Explores how to utilize the chat format to engage in extended conversations with ChatGPT, personalizing interactions for specific tasks or behaviors. | `ChatGPT`, `Chat Format`, `Conversational AI` | [Notebook Link](notebook/chat_format_chatgpt.ipynb) |
| **Language Models, the Chat Format, and Tokens in ChatGPT** | Explores the fundamentals of language models, the structure of the chat format used in ChatGPT, and the concept of tokens in natural language processing. | `ChatGPT`, `Language Models`, `Chat Format`, `Tokens`, `NLP` | [Notebook](notebook/language_models_chat_format_tokens_chatgpt.ipynb) |
| **Evaluate Inputs: Classification** | Focuses on classifying customer queries to effectively handle various cases. This section demonstrates how to leverage classification techniques to improve response accuracy and relevance in ChatGPT interactions. | `ChatGPT`, `Classification`, `Customer Queries`, `NLP` | [Notebook](notebook/evaluate_inputs_classification_chatgpt.ipynb) |
| **Evaluate Inputs: Moderation** | Covers the use of the OpenAI Moderation API for evaluating and moderating inputs in ChatGPT. Highlights the importance of ensuring content safety and compliance with guidelines. | `ChatGPT`, `Moderation API`, `OpenAI` | [Notebook](notebook/evaluate_inputs_moderation_chatgpt.ipynb) |
| **Chain of Thought Reasoning with ChatGPT** | Demonstrates using Chain of Thought reasoning in ChatGPT to process inputs through logical step-by-step analysis, enhancing response quality and coherence. | `ChatGPT`, `Chain of Thought Reasoning`, `Input Processing`, `NLP` | [Notebook](notebook/process_inputs_chain_of_thought_chatgpt.ipynb) |
| **Chaining Prompts with ChatGPT** | Explores implementing complex tasks by chaining multiple prompts in ChatGPT, allowing for structured and sequential handling of multi-step tasks. | `ChatGPT`, `Chaining Prompts`, `Multi-Step Tasks`, `NLP` | [Notebook](notebook/process_inputs_chaining_prompts_chatgpt.ipynb) |
| **Check Outputs in ChatGPT** | Details methods to verify ChatGPT outputs, including checking for potentially harmful content and ensuring factual accuracy based on provided product information. | `ChatGPT`, `Output Validation`, `Content Safety`, `Factual Accuracy` | [Notebook](notebook/check_outputs_chatgpt.ipynb) |
| **Build an End-to-End System** | Combines a series of chained prompts to process user queries. Includes a function for collecting user and assistant messages over time and instructions for interacting with the chatbot. The system message contains detailed guidance for OrderBot's tasks. | `End-to-End System`, `Chained Prompts`, `Chatbot`, `OrderBot` | [Notebook](notebook/end_to_end_system.ipynb) |
| **Evaluation in ChatGPT** | Covers evaluating LLM responses in two scenarios: (1) cases with a single right answer focusing on accuracy and precision, and (2) cases with multiple valid answers, emphasizing diversity, relevance, and coherence. | `LLM Evaluation`, `ChatGPT`, `Accuracy`, `Response Quality` | [Notebook 1](notebook/evaluation_part_I_chatgpt.ipynb), [Notebook 2](notebook/evaluation_part_II_chatgpt.ipynb) |
| **Normalizing the Content using Unstructured** | Extracts and normalizes content from various document types, including PDFs, PowerPoints, Word documents, HTML files, tables, and images, to expand the information accessible to the LLM. Utilizes the Unstructured library for effective content handling. | `Unstructured`, `Content Extraction`, `Normalization`, `Document Processing` | [Notebook](preprocessing-unstructured-data/normalizing_content.ipynb) |
| **Metadata Extraction and Chunking using Unstructured and ChromaDB** | Demonstrates the extraction of metadata and chunking of content using the Unstructured library and ChromaDB for efficient data handling and retrieval. | `Unstructured`, `ChromaDB`, `Metadata Extraction`, `Chunking` | [Notebook](preprocessing-unstructured-data/metadata_extraction_chunking.ipynb) |
| **Preprocessing PDFs and Images using Unstructured** | Applies layout detection and vision transformers to preprocess PDFs and images, enhancing the extraction and normalization of content for further analysis. | `Unstructured`, `PDF Processing`, `Image Processing`, `Layout Detection` | [Notebook](preprocessing-unstructured-data/preprocessing_pdfs_images.ipynb) |
| **Extracting Tables using Unstructured** | Focuses on techniques for document image analysis, including layout detection and vision transformers, to effectively extract tables from various document formats. | `Unstructured`, `Table Extraction`, `Document Analysis`, `Layout Detection` | [Notebook](preprocessing-unstructured-data/extracting_tables.ipynb) |
| **RAG Bot using OpenAI, LangChain, ChromaDB, and Unstructured** | Builds a Retrieval-Augmented Generation (RAG) bot capable of ingesting various document types, including PDFs, PowerPoints, and Markdown files, leveraging the capabilities of OpenAI, LangChain, ChromaDB, and Unstructured. | `OpenAI`, `LangChain`, `ChromaDB`, `Unstructured`, `RAG` | [Notebook](preprocessing-unstructured-data/rag_bot.ipynb) |
| **Large Language Models with Semantic Search** | Implements various techniques for enhancing search capabilities, including basic keyword search, enhancement with the rerank method for relevance ranking, dense retrieval using embeddings for improved semantic search results, and generating answers through LLM integration. | `Semantic Search`, `Keyword Search`, `Embeddings`, `ReRank`,`Cohore`,`weaviate` | [Keyword Search](semantic_search/keyword_search.ipynb), [Embeddings](semantic_search/embeddings.ipynb), [Dense Retrieval](semantic_search/dense_retrieval.ipynb), [ReRank](semantic_search/rerank.ipynb), [Generating Answers](semantic_search/generating_answers.ipynb) |






The repository is frequently updated with new tutorials, use cases, and technical guides to ensure it remains a valuable resource for learning and implementing LLM technologies.

## Contribution 🤝

The **LLM AtoZ** repository welcomes contributions from the community. All contributions should align with the repository's standards for quality and consistency. Contributions may include:
- New tutorials, notebooks, or examples.
- Enhancements to existing code and documentation.
- Bug fixes or optimizations.

Contribution Process:
1. Fork the repository.
2. Create a new branch for your contribution.
3. Submit a pull request with a clear explanation of the changes.

All submissions are subject to review to ensure they meet the high standards of the repository.

## Acknowledgments 🙌

This repository is built on the foundational work of several leading organizations in AI and NLP. Special recognition goes to:
- **DeepLearning.AI**
- **Hugging Face**
- **Nexusflow.ai**
- **LangChain**
- **OpenAI**
- **Gemini**
- **Cohore**

The tools and frameworks from these organizations have been instrumental in the creation of this repository.

## License 📄

This repository is licensed under the [MIT License](LICENSE). This license allows modification, distribution, and use of the code for both personal and commercial purposes, as long as the original license and copyright notices are retained.