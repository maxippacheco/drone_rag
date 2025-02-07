# Drone Detection and Tracking with LlamaIndex

This project demonstrates the use of LlamaIndex for answering questions related to drone detection and tracking. It uses various indexing techniques to retrieve information from a collection of documents.

## Core Functionalities:

1. **Data Collection and Processing:**
- Fetches content from diverse online sources related to drones, object detection, and computer vision.
- Cleans the fetched content to remove irrelevant sections and formatting.
- Stores the processed data in text files for indexing.

2. **Indexing with LlamaIndex:**
- Creates different types of indexes using LlamaIndex:
    - **Vector Store Index:** Enables semantic search based on document embeddings.
    - **Tree Index:** Organizes documents hierarchically for efficient retrieval.
    - **List Index:** Processes documents sequentially for simple queries.
    - **Keyword Table Index:** Extracts keywords for fast keyword-based search.

3. **Querying and Retrieval:**
- Allows users to ask questions related to drones and their applications.
- Utilizes the created indexes to retrieve relevant information from the document collection.
- Provides source nodes and scores for transparency and evaluation.

4. **Performance Evaluation:**
- Calculates query execution time for each indexing technique.
- Computes cosine similarity between the query and retrieved results to assess relevance.
- Offers performance metrics to compare the efficiency of different index types.
