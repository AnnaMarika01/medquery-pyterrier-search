# MedQuery: Medical Information Retrieval Search Engine

## Overview
This project implements a search engine for medical information retrieval using PyTerrier. 
It retrieves relevant answers to natural language queries, sourced from [NutritionFacts.org](https://nutritionfacts.org), by leveraging an index of medical documents. 
The implementation is provided as a **Python notebook**.

## Project Structure
- **Part I: Dataset Analysis**  
  - Analyze document collection, queries, and qrels.
  - Compute statistics: total terms per document, stemmed tokens, stopwords, and qrels distribution.

- **Part II: Basic Retrieval Pipelines**  
  - Index the document collection using PyTerrier with different stemmers.
  - Develop baseline retrieval pipelines (TF-IDF, BM25).
  - Evaluate offline retrieval effectiveness (Precision@k, Recall@k, MAP, nDCG).

- **Part III: Performance Enhancement**  
  - Improve baseline performance via:
    - Query expansion (using word embeddings or LLMs).
    - Neural re-ranking approaches.

## Dataset
- https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/