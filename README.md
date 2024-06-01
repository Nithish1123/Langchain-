ChatGPT-Enhanced Q&A System

This repository contains a ChatGPT-enhanced Q&A system built using LangChain and OpenAI. The system leverages a combination of CSV and PDF document loaders to create a vector database for answering questions based on context retrieved from the documents. Additionally, it can predict the next set of questions based on the user's current question.

Features
Load and process data from CSV files and PDFs.
Create a vector database using FAISS for efficient retrieval.
Generate answers to user questions based on the context from the vector database.
Predict the next set of questions based on the current question.


Predicting Next Questions
To predict the next set of questions based on the current question:
The Predicting Next Questions feature enhances the Q&A system by anticipating follow-up queries based on the user's current question. Utilizing a combination of LangChain's prompt templates and the OpenAI language model, this functionality generates three relevant questions to continue the conversation. This predictive capability is particularly useful for creating more engaging and interactive user experiences, as it helps guide users through a series of related inquiries, ensuring a more comprehensive understanding of the topic at hand.
