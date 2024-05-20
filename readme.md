# Cohere GenAI demo for WiDS
Use this repo to play with RAG using the Python Cohere library. This walkthrough uses examples from Cohere's guide to making a [RAG enabled chatbot](https://cohere.com/blog/rag-chatbot), but skips the need for the unstructured- library dependency. Unstructured is fantastic for chunking websites and documents into vector friendly pieces, so you should definitely check it out of interested.

## Setup

Create an environment such as "cohere_demo" with Python == 3.10. After activating the environment, install other requirements using: 
```pip install -r requirements.txt```
**Note**: if you are on windows, you may need to install visual studio c++ to use [HNSWlib](https://js.langchain.com/docs/integrations/vectorstores/hnswlib)

Key requirements include:
- cohere: includes a chat client for Cohere's LLM and a reranker all in one library
- hnswlib for the vector library
- pandas for basic etl with csv text

## Get Cohere API
Go [here](https://dashboard.cohere.com/api-keys) to get an API key for the Cohere chatbot. The key is free for personal use, but costs for enterprise use. If you decide your company can benefit from RAG or Gen AI, you can consider using Cohere or stand-up your own LLMs using other free models and tools.
Copy the key into the config.py file to use to connect the client.

## Presentation Slides

The slides are under presentation/genai_intro.slides.html , converted from jupyter notebook of same name.

## Video of presentation

Click here for the video with intro from slides and walking through the notebook: [WiDS DC 2024- GenAI_RAG intro ](https://drive.google.com/file/d/1E48bX74dNTT_3CrP7hkfYz_PVah8pTwm/view?usp=sharing)






