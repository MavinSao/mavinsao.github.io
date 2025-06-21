---
title: "Beyond Keywords: BERTopic and Mistral-8B Integration for Smartphone User Perception Analysis"
collection: poster
type: "Poster Presentation"
permalink: /thesis/2025-smartphone-user-perception
venue: "2025 Spring Joint Conference on Industrial Innovation"
date: 2025-06-18
location: "Haevichi Hotel & Resort, Jeju, South Korea"
---


![1_Presentation](/images/conference/jeju_2.jpg)

## Abstract

Online forums provide rich but unstructured feedback from smartphone users. Traditional analysis methods struggle to extract meaningful themes from such content. This study introduces a hybrid analytical pipeline that combines **BERTopic** for clustering and **Mistral-8B** for semantic refinement. The system analyzes discussions about the iPhone 15 and Galaxy S23 series from Reddit and Whirlpool forums, delivering clear topic labels and sentiment summaries to enhance user perception analysis.

## Methodology

![Poster Presentation 1](/images/conference/method.png)

The pipeline consists of five main steps:  
1. Data collection and preprocessing  
2. Sentence embedding using all-MiniLM-L6-v2  
3. Dimensionality reduction with UMAP  
4. Clustering using HDBSCAN  
5. Topic labeling and summarization using Mistral-8B and sentiment analysis via VADER

This method allows for interpretable and scalable insight extraction from large-scale user discussions.
