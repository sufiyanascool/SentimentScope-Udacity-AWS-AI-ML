# SentimentScope: Sentiment Analysis using Transformers

[![Udacity - Future AWS AI & ML Programmer](https://img.shields.io/badge/Udacity-Future%20AWS%20AI%20%26%20ML%20Programmer-02B3E4?style=for-the-badge&logo=udacity&logoColor=white)](https://www.udacity.com/)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](./LICENSE)

## 📋 Overview

This project is part of the **Udacity AI & ML Nanodegree — Future AWS AI Programmer** program. The goal is to build a **transformer-based sentiment analysis model from scratch** using PyTorch to classify IMDB movie reviews as **positive** or **negative**.

I am  playing the role of a Machine Learning Engineer at **Cinescope**, a growing entertainment company looking to enhance its recommendation system by understanding user sentiment from movie reviews.

## 🎯 Learning Objectives

- Load, explore, and prepare a text dataset for training a transformer model using PyTorch.
- Customize the architecture of a transformer model for a binary classification task.
- Train and evaluate the transformer model on the IMDB dataset.
- Achieve **>75% accuracy** on the test set.

## 📁 Project Structure

```
SentimentScope/
├── SentimentScope_starter.ipynb   # Main project notebook
├── README.md                      # Project documentation
├── requirements.txt               # Python dependencies
├── LICENSE                        # MIT License
└── .gitignore                     # Git ignore rules
```

## 📊 Dataset

The project uses the [IMDB Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/) containing **50,000 movie reviews** split evenly into training and test sets, with a 50/50 positive/negative label distribution.

| Split    | Positive Reviews | Negative Reviews | Total  |
|----------|-----------------|-----------------|--------|
| Training | 12,500          | 12,500          | 25,000 |
| Testing  | 12,500          | 12,500          | 25,000 |

## 🏗️ Project Notebook Sections

1. **Load, Explore, and Prepare the Dataset** — Load the IMDB dataset, explore it with visualizations, and split it into training and validation sets.
2. **Implement a DataLoader in PyTorch** — Create the `IMDBDataset` class with tokenization and use it with the PyTorch `DataLoader`.
3. **Customize the Transformer Architecture** — Modify the transformer model architecture for binary classification.
4. **Implement Accuracy Calculation** — Create a function to compute accuracy for monitoring performance.
5. **Train the Model** — Complete and execute the training loop for binary classification.
6. **Test the Model** — Evaluate the model on the test dataset and ensure it achieves over 75% accuracy.
7. **Conclusion** — Summarize results and key takeaways.

## 🛠️ Tech Stack

- **Python 3.8+**
- **PyTorch** — Model architecture, DataLoader, training loop
- **Pandas** — Data exploration and manipulation
- **Matplotlib** — Data visualization
- **NumPy** — Numerical operations

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sufiyanascool/SentimentScope-Udacity-AWS-AI-ML.git
   cd SentimentScope-Udacity-AWS-AI-ML
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Download and extract the dataset:**

   The IMDB dataset (`aclImdb_v1.tar.gz`) should be placed in the project root directory. The notebook includes a cell to extract it.

4. **Open the notebook:**

   ```bash
   jupyter notebook SentimentScope_starter.ipynb
   ```

## 📝 Usage

Run the notebook cells sequentially from top to bottom. Each section contains detailed instructions and explanations. Key tasks marked with `TODO` or instructions require your implementation.

## 📈 Results

The trained transformer model achieves **>75% accuracy** on the IMDB test set for binary sentiment classification.

## 🙏 Acknowledgments

- [Udacity](https://www.udacity.com/) — AI & ML Nanodegree: Future AWS AI Programmer program
- [Stanford AI Lab](https://ai.stanford.edu/~amaas/data/sentiment/) — IMDB Large Movie Review Dataset
- [PyTorch](https://pytorch.org/) — Deep learning framework

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

---

> **Note:** This project was completed as part of the Udacity AI & ML Nanodegree — Future AWS AI Programmer program. The starter code and project outline were provided by Udacity.
