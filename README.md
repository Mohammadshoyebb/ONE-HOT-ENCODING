# **ONE-HOT ENCODING**

One-hot encoding is a technique used to convert categorical data into a format that can be provided to machine learning algorithms. Here's an example of how one-hot encoding can be implemented using Keras:

```python
from keras.utils import to_categorical

# Example categorical data (class labels)
class_labels = [0, 1, 2, 1, 0]

# One-hot encoding using Keras to_categorical
one_hot_encoded = to_categorical(class_labels)

print("Original Labels:")
print(class_labels)

print("\nOne-Hot Encoded Matrix:")
print(one_hot_encoded)```


# One-Hot Encoding and Simple Word2Vec Implementation

This repository contains Python scripts demonstrating the implementation of One-Hot Encoding and Simple Word2Vec using popular deep learning libraries such as Keras and TensorFlow. Below is a breakdown of each implementation:

## One-Hot Encoding

### Overview

*One-hot encoding* is a technique used to convert categorical data into a binary matrix format. Each category is represented as a binary vector with only one element of the vector set to 1, indicating the presence of that category.

### Implementation

The implementation showcases how to convert categorical labels into a **one-hot encoded matrix** using Keras `to_categorical` function.

## Simple Word2Vec

### Overview

*Word2Vec* is a popular technique for learning word embeddings, which are dense vector representations of words in a continuous vector space. It captures semantic relationships between words based on their contextual usage in a corpus of text.

### Implementation

The implementation outlines the steps involved in training a simple Word2Vec model using TensorFlow and Keras:

- **Corpus Preparation**: Tokenizing the corpus into words and creating vocabulary.
- **Generating Training Data**: Creating target and context word pairs from the tokenized corpus.
- **Model Definition**: Defining a simple Word2Vec model architecture using Embedding and Dense layers.
- **Training**: Training the Word2Vec model to learn word embeddings from the generated training data.

## Conclusion

This README.md provides a high-level overview of implementing One-Hot Encoding and Simple Word2Vec using Python, Keras, and TensorFlow. These techniques are fundamental in natural language processing tasks such as text classification, sentiment analysis, and machine translation. The provided information serves as a foundational guide for understanding and applying these techniques in various NLP applications.
