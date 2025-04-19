# Representation Learning through Skip-Gram with Negative Sampling 

SkipGram is a foundational NLP project that demonstrates how to learn meaningful word representations using contextual information. It captures semantic relationships between words by training a shallow neural network on context-target word pairs, implemented entirely from scratch using Python and NumPy.

## Features
Tokenization & Vocabulary Construction: Converts raw text into a tokenized corpus and builds a vocabulary dictionary.

- Contextual Pair Generation: Generates center-context word pairs based on a defined window size.

- Negative Sampling: Optimizes training by introducing efficient approximation for softmax through negative examples.

- Cosine Similarity Evaluation: Measures semantic closeness between word vectors to validate learning.

## Description
- Developed a word embedding model using the Skip-Gram architecture to learn contextual word representations from raw text.

- Preprocessed the dataset to tokenize words and generate context-target pairs with sliding windows.

- Implemented training logic using NumPy, including negative sampling and gradient descent updates.

- Evaluated word relationships by computing cosine similarity between embedding vectors, showcasing the model’s semantic understanding.

## Project Structure
- SkipGram.ipynb: Jupyter Notebook containing the full pipeline including training, evaluation, and inline explanations.
