# Item Cluster Topic Modeling (`item_cluster_103.ipynb`)

## Overview

This project focuses on identifying and grouping similar textual items into clusters using advanced Natural Language Processing (NLP) and Topic Modeling techniques. The main goal is to extract meaningful insights and underlying themes from unstructured text data.

## Objective

- Implement efficient preprocessing and feature extraction methods.
- Leverage clustering and topic modeling algorithms (BERTopic) to discover underlying patterns.
- Provide visual and quantitative evaluation of topic modeling results.

## Key Libraries Used

- **Pandas & NumPy** for data handling and manipulation
- **Scikit-learn** for text preprocessing and clustering (`CountVectorizer`, `TfidfVectorizer`, `PCA`, `KMeans`)
- **BERTopic** for advanced topic modeling
- **UMAP & HDBSCAN** for dimensionality reduction and density-based clustering
- **Jellyfish & Fuzzywuzzy** for text similarity
- **Matplotlib, Seaborn & WordCloud** for data visualization
- **ydata-profiling** for exploratory data analysis (EDA)

## Data

The dataset (`data_materials.csv`) contains textual descriptions requiring preprocessing and cleaning to perform accurate topic modeling and clustering.

## Workflow

1. **Data Import and Inspection**: Load and explore data structure.
2. **Text Preprocessing**: Remove stop words, clean text data.
3. **Feature Extraction**: Convert text to numerical representations using vectorization techniques (`CountVectorizer`, `TF-IDF`).
4. **Topic Modeling and Clustering**: Apply BERTopic for topic extraction and identify meaningful clusters using UMAP and HDBSCAN.
5. **Visualization**: Generate informative visuals (word clouds, dendrograms, PCA plots) to interpret and communicate findings clearly.
6. **Insights and Evaluation**: Extract frequent terms and thematic clusters to provide actionable insights.

## Usage

- Install the required libraries listed in the notebook.
- Update the dataset path (`data_materials.csv`) as necessary.
- Run cells sequentially to follow the analytical workflow and interpret results.

## Applications

This implementation can be adapted for:

- Product categorization
- Customer feedback analysis
- Market research
- Trend detection in textual datasets

## Author

**Lorenzo Cardenas**

