# New Article Categorization

This project focuses on categorizing new articles into 5 predefined labels using **Sentence Transformers** for text embedding and **K-means clustering** for unsupervised learning.

## 🧠 About

The task is to categorize news articles into 5 distinct labels. The approach involves transforming sentences into vector embeddings using **Sentence Transformers** and then applying **K-means clustering** to assign these articles into the appropriate categories. This unsupervised approach helps in organizing articles without manually labeled data.

## 🚀 Key Steps

- **Text Embedding**: Used **Sentence Transformers** to convert text (news articles) into vector embeddings that capture the semantic meaning of each sentence.
- **Clustering**: Applied the **K-means algorithm** to cluster the sentence embeddings into 5 clusters (labels).
- **Label Creation**: Generated 5 labels based on clustering results, each representing a category of news articles.

## 🔍 Dataset

- **Source**: The dataset can be sourced from various publicly available news datasets (such as custom news data).
- **Preprocessing**: Tokenization, lowercasing, stopword removal, and sentence embedding using the Sentence Transformers library.


## 🧾 Requirements

- sentence-transformers
- sklearn
- pandas
- numpy
- matplotlib
- nltk

---
