# RAG Mini Demo
This repository contains a lightweight, functional implementation of the retrieval half of a Retrieval-Augmented Generation (RAG) system built using ChromaDB.
* **Project Overview**
LLMs are bounded by their training data cutoffs and lack access to proprietary corporate knowledge bases. This project demonstrates the core architectural pattern used to solve this: Semantic Retrieval.

The script initializes a vector store, indexes a set of sample corporate compliance documents, and runs a natural language query to retrieve contextually relevant results based on meaning rather than exact keyword matches.

* **Key Components:**
Vector Database: ChromaDB (In-memory client)

Embedding Model: all-MiniLM-L6-v2 (Defaulted locally by ChromaDB)

Dataset: Synthetic corporate payment and cancellation policies
