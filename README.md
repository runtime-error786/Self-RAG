## Overview

This project implements a Retrieval-Augmented Generation (RAG) chain using a local LLM (Llama3) and the LangChain framework. It focuses on enhancing question answering by improving document retrieval, filtering relevant document, re-generating questions, and scoring the generated responses. This setup allows for more accurate and contextually relevant responses based on retrieved documents.

## Features


Document Retrieval: Retrieve documents from URLs and filter them based on relevance to the query.



RAG Generation: Use the retrieved documents for contextual generation with Llama3.


Question Transformation: Optimize user questions for better retrieval results.



Grading Mechanism: Grade the relevance of documents and the grounding of generated answers.






Hallucination Detection: Identify whether the generated content is grounded in the retrieved documents.



Useful Answer Assessment: Grade generated answers to determine if they address the user’s question.



![output](https://github.com/user-attachments/assets/cd1649ab-bc99-48d2-94ae-73ef3cbc0be0)

