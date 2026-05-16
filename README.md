# Simple RAG-Pipeline
This Project is beginner friendly tutorial project for building a Retrieval Augmented Generation (RAG) Systems. It demonstrates how to index documents, retrieve relevant content, Generative AI- powered responses and evaluate results--- all through a command line interface(CLI).

![rag-image](./rag-design-basic.png)
#Overview:

The Rag Frame work lets you:
*Index Document: Process and break documents embeddings in vector
Retieval Augmented Generation
# Why RAG Needed.?
Retrieval Augmented Generation (RAG) is needed because of overcome the limitations of Large Language Models(LLM), such as knowledge, hallucinations, and inability to accesss private data. RAG connects LLM's to provide specific knowledge, domain specific, and up-to date specific information.

## RAG Database Detail:

## Architecture
Pipeline
Orchestrates the process using:
    Datastore: Manages embeddings and vector storage.
    Indexer: Processes documents and creates data chunks. Two versions are available--a basic PDF indexer and one using the Docling package.
    Retriever: Searches the datastore to pull relevant document segments.
    ResponseGenerator: Generates answers by calling the AI service.
    Evaluator: Compares the AI response to expected answers and explains the outcome.
Interfaces (interface/):
    Abstract base classes define contracts for all components (e.g. BaseDatastore, BaseIndexer, BaseRetriever, BaseResponseGenerator, and BasaeEvaluator), making it easy to extend or swap implementations.

# Stack

Python
Next Js

Libraries:
Data Pipeline and details.
Cloud:

e


# Installation:


