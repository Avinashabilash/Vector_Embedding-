# 🌟 Word Embedding Analogy Project

 

## 🚀 Project Overview
The **Word Embedding Analogy Project** explores the fascinating world of **word embeddings** and **semantic relationships** between words. Using pre-trained embeddings like **GloVe** and **SentenceTransformers**, this project evaluates analogies, such as **male-female**, **country-language**, and more. It demonstrates how machines can understand word similarities and relationships through **vector arithmetic**.

---

## 🎯 Goal
- To learn and implement **word embeddings** for semantic analysis.
- To evaluate **analogical reasoning** using word vectors.
- To create a framework for exploring **relationships between words** in a vector space.

---

## 📝 Objectives
1. Load and process pre-trained embeddings (GloVe / Transformers).  
2. Build a dataset of word pairs (male-female, country-language, etc.).  
3. Compute **cosine similarity** to predict relationships between words.  
4. Evaluate analogy accuracy and analyze results.  
5. Provide a reusable Python framework for word analogy experiments.

---

## 📚 Table of Contents
- [Project Overview](#-project-overview)  
- [Goal](#-goal)  
- [Objectives](#-objectives)  
- [Methodology](#-methodology)  
- [Installation & Setup](#-installation--setup)  
- [Usage](#-usage)  
- [Dataset](#-dataset)  
- [Results](#-results)  
- [Contributing](#-contributing)  

---

## 🧰 Methodology
1. **Load Pre-trained Embeddings**  
   - Load **GloVe embeddings** (`glove.6B.100d.txt`) for static word vectors.  
   - Optionally use **SentenceTransformer** models (`all-MiniLM-L6-v2`) for contextual embeddings.  

2. **Preprocess Dataset**  
   - Load analogy pairs (male-female, country-language, etc.) from `.txt` files.  
   - Clean data and split multiple word options (`mom/mother/mommy`).  

3. **Vector Computation & Normalization**  
   - Compute vectors for each word.  
   - Normalize vectors for cosine similarity calculations.  

4. **Analogy Solving**  
   - For a pair `(word_a, word_b)`, find `word_c` such that `word_a : word_b :: word_c : ?`.  
   - Use **cosine similarity** or **vector arithmetic** (`vec_b - vec_a + vec_c`).  

5. **Evaluation**  
   - Compare predicted word with actual `word_d`.  
   - Compute **accuracy** and analyze semantic performance.  

---
🗂 Dataset

Male-Female Pairs (male-female.txt)

Extended Analogy Dataset (E10 [male - female].txt)

Other semantic pairs (optional: country-language, animal sounds, etc.) 

📖 References

GloVe: Global Vectors for Word Representation

SentenceTransformers Documentation

Word Embedding Analogies

## ⚙️ Installation & Setup
1. **Clone the repository**  
```bash
git clone https://github.com/Avinashabilash/vector_embedding.git
cd vector_embedding

