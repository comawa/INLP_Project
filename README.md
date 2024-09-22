# INLP_Project

This project, **INLP_Project**, focuses on Natural Language Processing (NLP) tasks and makes use of various powerful libraries for working with text data and machine learning models. The project is managed with **Mamba** for creating a clean Python environment. 

## Project Dependencies

The following key packages are used in this project:

### 1. `datasets` (by Hugging Face)
- Provides simple tools for downloading and preprocessing NLP datasets.
- Supports access to a wide variety of publicly available NLP datasets to integrate directly into machine learning projects.

### 2. `gensim`
- A toolkit for working with unstructured text data, especially useful for training vector space models like Word2Vec, Doc2Vec, and FastText.
- Ideal for tasks like topic modeling, document similarity calculations, and other text mining applications.

### 3. `torch` (PyTorch)
- A popular machine learning library developed by Facebook AI Research, primarily used for deep learning and neural networks.
- Particularly useful for NLP tasks involving sequence data, such as recurrent neural networks (RNNs) or Transformer-based models.

### 4. `nltk` (Natural Language Toolkit)
- One of the oldest and most comprehensive libraries for NLP in Python.
- Provides functions for tokenization, stemming, parsing, semantic analysis, and other fundamental NLP tasks.

### 5. `transformers` (by Hugging Face)
- Includes pre-trained Transformer models such as BERT, GPT, and RoBERTa for tasks like text classification, translation, text generation, and question answering.
- Simplifies the implementation of powerful NLP models without needing to train them from scratch.

### 6. `numpy`
- A core library for scientific computing in Python, offering efficient support for large, multi-dimensional arrays and matrices.
- Frequently used in NLP to represent and process text data and models as numerical arrays.

### 7. `scikit-learn`
- Provides various machine learning functions, including classical algorithms for classification, regression, and clustering.
- Commonly used in NLP for implementing machine learning algorithms like Support Vector Machines (SVMs), k-Means clustering, or decision trees on text data.

## Setting Up the Environment

To create a clean environment and install the required dependencies using Mamba, follow these steps:

### Step 1: Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/comawa/INLP_Project.git
cd INLP_Project
```

### Step 2: Create and Activate the Environment
- Ensure you have Mamba installed.

```bash
mamba env create -f environment.yml
conda activate Python310INLP
```

### Step 3: Install the Jupyter Kernel
To register the environment with Jupyter so that it can be used in Notebooks, run the following command:

```bash
python -m ipykernel install --name KernelPython310INLP --disply-name "Python 310 (INLP_Project)"
```

### Step 4: Launch JupyterLab
Start JupyterLab to work with the project:

```bash
jupyter lab
```

## Usage
Once the environment is set up, you can open and run the Jupyter Notebooks within the repository to explore the various NLP tasks and models.


