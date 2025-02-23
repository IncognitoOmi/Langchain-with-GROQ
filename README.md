# LangChain Practical Implementations with Groq API

## Overview
This repository contains practical implementations of LangChain features using the Groq API. It demonstrates how to manage multiple chat sessions, generate responses in different languages, and trim chat history efficiently.

## Features
- **Groq API Integration**: Securely storing and using the Groq API key.
- **Multiple Session Handling**: Utilizing `BaseChatMessageHistory`, `ChatMessageHistory`, and `RunnableWithMessageHistory` for managing different chat sessions.
- **Multilingual Responses**: Fetching chat responses in different languages.
- **Chat History Management**: Trimming previous chat history to optimize performance.
```

## Libraries required
langchain
nest-asyncio
psutil
tornado>=6.1
traitlets>=5.4.0
ipython
python-dotenv
langchain-openai
langchain-core
langchain_community
bs4
faiss-cpu
langchain_groq
