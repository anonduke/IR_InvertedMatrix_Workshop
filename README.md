# IR Inverted Index Lab: README

## Overview
This lab focuses on building an Information Retrieval (IR) inverted index pipeline using Python. The goal is to enable fast document retrieval and phrase querying, which are essential skills for search engines and NLP applications.

## Objectives
- Build a term-document inverted index and a positional inverted index.
- Preprocess documents through tokenization, stopword removal, and stemming.
- Perform Boolean queries using AND, OR, and NOT operations.
- Perform exact phrase queries using positional indexing.

## Steps Completed
1. Document Loading: Load text files from a folder into a list for processing.
2. Tokenization: Convert text into lowercase words and remove punctuation.
3. Normalization: Remove stopwords using nltk and apply stemming.
4. Vocabulary Building: Create a set of unique, normalized tokens.
5. Inverted Index: Build a basic inverted index (term mapped to document IDs) and a positional inverted index (term mapped to document IDs with positions for phrase support).
6. Boolean Queries: Retrieve documents that match specific terms using AND, OR, and NOT.
7. Phrase Queries: Retrieve documents that contain exact phrases using positional matching.

## Example: Phrase Queries
```python
query1 = "machine learning"
query2 = "deep model"

print("Documents with the phrase 'machine learning':", phrase_query(query1, positional_inverted_index))
print("Documents with the phrase 'deep model':", phrase_query(query2, positional_inverted_index))
```

## Key Takeaways
- Understanding how IR systems index and retrieve documents efficiently.
- Practical experience implementing inverted indexing pipelines.
- Clarity on the difference between Boolean retrieval and phrase retrieval.
- Experience in preparing text datasets for retrieval tasks in NLP and ML projects.

## Next Steps
- Add evaluation metrics like precision and recall to measure retrieval effectiveness.
- Explore TF-IDF weighting to rank retrieved documents by relevance.
- Build a simple search interface using your inverted index for practical use.

This README will help you document and present your IR lab work clearly for submissions, demonstrations, and your personal study notes.