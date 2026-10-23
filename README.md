# Cryptography Algorithm Classification & Identification Engine

A machine learning and deep learning pipeline designed to classify cryptographic algorithms (AES, DES, RSA, Blowfish, etc.) based on ciphertext statistical properties, length, entropy, and variance.

## Features
- **Data Preprocessing**: Extracts ciphertext length, byte-level entropy, and statistical variance from encrypted byte streams.
- **Modeling**: Implements both Keras Neural Networks (MLP) with class balancing and Scikit-Learn Random Forest classifiers.
- **Evaluation**: Evaluates multi-class classification using precision, recall, and F1-score metrics.

## Tech Stack
- **Languages**: Python
- **Libraries**: TensorFlow/Keras, Scikit-Learn, Pandas, NumPy, Matplotlib