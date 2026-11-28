# Day 5 – Retrieval-Augmented Generation (RAG)

## Workshop
One Person Company – AI Agents Workshop

## Project
Sweet Crumbs Home Bakery AI Assistant

## Overview
On Day 5, I learned about Retrieval-Augmented Generation (RAG) and how it helps AI applications provide accurate answers using external documents as a knowledge source.

I explored how an AI system can retrieve relevant information from documents and use that information to generate context-based answers instead of depending only on the LLM's pre-trained knowledge.

As a practical exercise, I worked with a PDF story called **The Little Lantern** and built a basic RAG pipeline using Python, LangChain, Hugging Face embeddings, FAISS, and Groq.

## Topics Learned

1. **Introduction to RAG:** Understanding how Retrieval-Augmented Generation combines document retrieval with LLM-based answer generation.
2. **Document Loading:** Loading PDF documents and extracting their text using PyPDFLoader.
3. **Text Splitting:** Dividing large documents into smaller chunks using RecursiveCharacterTextSplitter.
4. **Text Embeddings:** Converting text chunks into numerical vector representations using Hugging Face embeddings.
5. **Vector Database:** Understanding how FAISS stores and searches vector embeddings efficiently.
6. **Similarity Search:** Finding the most relevant document chunks based on a user's question.
7. **Context-Based Answer Generation:** Providing retrieved information to an LLM so it can generate answers grounded in the document.
8. **Hallucination Reduction:** Learning how RAG can reduce unsupported answers by instructing the model to answer only from retrieved context.
9. **Reusable RAG Function:** Creating a function to ask multiple questions and retrieve answers from the uploaded PDF.

## Technologies Used

- Python
- Google Colab
- LangChain
- Hugging Face Sentence Transformers
- FAISS
- Groq LLM API
- PyPDF

## Practical Implementation

Built a basic RAG pipeline with the following workflow:

1. Uploaded the PDF document.
2. Extracted text from the PDF.
3. Split the extracted text into smaller chunks.
4. Generated embeddings for each chunk.
5. Stored the embeddings in a FAISS vector store.
6. Retrieved relevant chunks using similarity search.
7. Passed the retrieved context to the Groq LLM.
8. Generated answers based on the document content.

## Key Learnings

- Understood the working process of a RAG-based AI application.
- Learned how embeddings represent text in numerical form.
- Understood the role of vector databases in information retrieval.
- Learned how to connect document retrieval with an LLM.
- Understood why providing relevant context helps improve answer accuracy.
- Learned how to handle questions when the required information is not available in the document.

## Outcome

Successfully explored and implemented the basic Retrieval-Augmented Generation workflow using a PDF document. This practical exercise helped me understand how AI applications can use external knowledge sources to generate more relevant and context-aware responses.

## Day 5 Status
Completed – RAG concepts and practical implementation.
