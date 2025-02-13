# Retrieval-Augmented Generation in a Low Lexical Diversity Scenario
## Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Methodology](#methodology)  
- [Experiments](#experiments)   
- [Conclusion](#conclusion)   
- [References](#references)  
## Introduction
This repository contains the implementation of our study on Retrieval-Augmented Generation (RAG) in a low lexical diversity setting, specifically for classifying gas pipe damage descriptions based on their patchability.

Our work introduces a new lexical entropy metric to quantify textual diversity and proposes [+]EXPL, a data re-balancing technique that improves retrieval effectiveness in highly imbalanced datasets. The retrieval system is based on SBERT-NLI embeddings, while Mistral7B serves as the generative model for classification.

## Features
- Implements **Retrieval-Augmented Generation (RAG)** for classification.
- Introduces **Corpus Lexical Entropy** as a diversity metric.
- Uses **FAISS** for fast retrieval of similar cases.
- Employs **SBERT-NLI** embeddings for document representation.
- Integrates **Mistral7B** for classification.
- Proposes **[+]EXPL**, a downsampling strategy to mitigate class imbalance.
