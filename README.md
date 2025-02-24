# LLMRAGProject

Objectives
Business use case: As a product manager, I can use a chatbot system to conduct quick analysis of a company during my market research process. For example, the analysis will include key elements of a SWOT in a predefined structure that covers key points from financial documents such as 10K annual report of companies and can incroporate the analysis with real-time market news.

Technical Implmentation of the Prtotype: Phase I. User can store 10K annual reports and we will experiment on using the get text embedding gte-Qwen2-7B-instruct model (top performing from leaderboard + open source + smaller model) from hugging face to convert texts in to vectors; then use TinyLlama LLM model (effiecient model for using in Colab) for the decodcing /Chatbot functionality.
