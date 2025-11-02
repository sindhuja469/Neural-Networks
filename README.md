# 🎬 IMDB Sentiment Classification using Neural Networks  
Evaluation of Neural Network Performance on IMDB Data**  

---

## Project Overview
This project focuses on building and evaluating **feed-forward neural networks** for sentiment classification using the **IMDB movie reviews dataset**.  
It explores multiple neural network configurations by changing architecture depth, number of hidden units, activation functions, loss functions, and applying regularization techniques.

The goal is to understand how these modifications affect model performance in terms of **accuracy** and **loss**.

---

## Objectives
- Load and preprocess IMDB dataset using **multi-hot encoding**.
- Build a **baseline neural network model** for binary sentiment classification.
- Experiment with:
  - Varying the **number of hidden layers**
  - Changing the **number of hidden units**
  - Using **different loss functions**
  - Testing **different activation functions**
  - Applying **dropout regularization**
- Compare performance across models.

---

## Dataset Description
- **Dataset:** [IMDB Movie Reviews](https://storage.googleapis.com/tensorflow/tf-keras-datasets/imdb.npz)
- **Word Index:** [IMDB Word Index JSON](https://storage.googleapis.com/tensorflow/tf-keras-datasets/imdb_word_index.json)
- **Total Reviews:** 50,000  
  - 25,000 training  
  - 25,000 testing  
- **Labels:** Binary (Positive = 1, Negative = 0)
- **Preprocessing:** Multi-hot encoding of words to represent reviews numerically.

---

## ⚙️ Environment Setup
Run this notebook in **Google Colab** or locally with the following dependencies:

# Clone the repository
git clone https://github.com/sindhuja469/Neural-Networks.git
cd Neuarl-Networks
# Open in Google Colab or Jupyter

```bash
pip install tensorflow numpy matplotlib
