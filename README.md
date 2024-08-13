# Advanced-AI

# Real Estate Agent LangChain Project

## Description

This project leverages the power of natural language processing (NLP) and machine learning to create a real estate agent chatbot that can help users make informed decisions. The project utilizes LangChain, a framework for developing applications with large language models (LLMs), to streamline various tasks in the real estate domain.

## Key Components

1. **Data Ingestion and Preprocessing:**
   - The project begins with data ingestion from various sources that have text data, image data, and more
   - Data preprocessing steps include cleaning and reformatting to prepare the data for analysis.
   - Used static data because real estate API's are expensive and Webscraping is not allowed in many places
     
2. **Language Model Integration:**
   - Utilizes the Gemini API's pretrained large language model to analyze and interpret real estate data.
   - The model is fine-tuned for a variety of tasks and can look through the datasets to find relevant real estate information, such as property valuation

3. **Details**
   - Conducted comprehensive research on LLM architectures to design a chatbot tailored for real estate needs.
   - Employed a multi-agent strategy using LangChain, incorporating a text-to-SQL agent for handling text queries, a CLIP agent for processing image data, and a reranking agent that applies cosine similarity to refine responses.
   - Focused on the text-to-SQL agent, crafted a robust database schema to store comprehensive housing data, and utilized the Gemini API to enable the agent to interpret and execute complex user queries.
   - Implemented advanced prompt engineering techniques to minimize erroneous responses, achieving a chatbot accuracy rate of 90%.

## Important Files
- langchain: https://github.com/adacersos/Advanced-AI/blob/main/real_estate_agent_langchain.ipynb
- Langgraph: https://github.com/adacersos/Advanced-AI/blob/main/real_estate_agent_langgraph.ipynb
- text to sql data: https://github.com/adacersos/Advanced-AI/blob/main/cleaned_houses_info_with_ID.csv
- clip image data: No longer have access to it
