
# 🧠 Mini Word Embedding from Scratch (Word2Vec-Style)

This project implements a **minimal Word2Vec-style word embedding model** from scratch using Python and NumPy. It uses the **Skip-gram architecture with Negative Sampling**, and visualizes word vectors using **PCA**.

---

## 📘 Features

- 🔤 Text preprocessing and tokenization
- 📚 Vocabulary creation
- 🔁 Skip-gram training pair generation
- 🧠 Training with negative sampling (custom SGD)
- 📊 Word vector visualization in 2D space (PCA)

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mini-word-embedding.git
cd mini-word-embedding
```

### 2. Install dependencies

This project only requires basic libraries:

```bash
pip install numpy matplotlib scikit-learn tqdm
```

### 3. Run the notebook

```bash
jupyter notebook mini_word_embedding.ipynb
```

---

## 🧪 Sample Output

Using this text:

```text
"king queen man woman king queen"
```

You'll train 10-dimensional word vectors and visualize them in 2D like this:

```
king     ●
queen    ●
man      ●
woman    ●
```

Words like `'king'` and `'queen'` will be placed close together if trained correctly.

---

## 📂 File Structure

```
📁 mini-word-embedding/
├── mini_word_embedding.ipynb     # Main notebook
├── README.md                     # You're here
```

---

## 🙌 Credits

Inspired by the original Word2Vec paper (Mikolov et al., 2013).

Feel free to fork, modify, or share!
