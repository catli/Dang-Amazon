## Dang-Amazon Custom Review Segmentation

The goal of this project is auto-tag customer reviews with categories based on
word texts.


Step 1: Tokenize words in text field, and normalize text (lower case and
only use roots)

Step 2: Create TFIDF or Avg/Max doc embeddings

Step 3: Use kmeans to generate customer clusters

Step 4: Based on the clusters, create some labels

