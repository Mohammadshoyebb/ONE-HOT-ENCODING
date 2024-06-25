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
print(one_hot_encoded)
