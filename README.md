# RAG From Scratch

This project is forked from [langchain-ai/rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch), a comprehensive tutorial series on building RAG (Retrieval Augmented Generation) applications from scratch.

## Original Repository

The original repository provides notebooks that accompany a [video playlist](https://youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x&feature=shared) that builds up an understanding of RAG from scratch, starting with the basics of indexing, retrieval, and generation.

![rag_detail_v2](https://github.com/langchain-ai/rag-from-scratch/assets/122662504/54a2d76c-b07e-49e7-b4ce-fc45667360a1)

## Modifications and Improvements

This fork includes the following changes and enhancements:

### 1. **Dependency Management**
   - Added `requirements.txt` with pinned versions to resolve implicit dependency issues
   - Upgraded to LangChain 1.x (langchain==1.2.7, langchain-core==1.2.7, langchain-community==0.4.1)
   - Updated to ChromaDB 1.4.1 with langchain-chroma 1.1.0

### 2. **LLM Provider Migration**
   - **Replaced OpenAI with Google Gemini**: All notebooks now use Google's Gemini models instead of OpenAI
   - Using `gemini-2.0-flash` as the primary LLM model via `langchain-google-genai`
   - Using `models/gemini-embedding-001` for embeddings via `GoogleGenerativeAIEmbeddings`

### 3. **API Updates**
   - Updated deprecated API calls to match LangChain 1.x syntax
   - Migrated to the new Google Generative AI SDK (google-genai==1.60.0, langchain-google-genai==4.2.0)

### 4. **Additional Dependencies**
   - Added RAGatouille (0.0.9.post2) for advanced RAG capabilities
   - Added Cohere (4.57.0) for additional embedding/retrieval options
   - Included utility packages: langchainhub, beautifulsoup4, youtube-transcript-api, pytube, tiktoken

## Video Playlist

[Original Video Playlist](https://www.youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x)
