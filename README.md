# Foundations of LLMs — Karyashala Hands-on (GenAI-Health 2026)

This repository contains the **presentation slides, hands-on notebook, and MCQ assessment** for the ANRF-PAIR sponsored Karyashala:

> **LLMs and GenAI: Foundations, Python Implementation, and Healthcare Applications**  
> February 28–March 1, 2026

The material introduces core concepts of modern Generative AI and provides practical exercises for participants.

---

## Repository Contents

### Presentation
**File:** `Karyashala.pptx`  
Covers the conceptual foundations:

- LLM processing pipeline  
- Tokenization techniques  
- Embedding space intuition  
- Transformer self-attention  
- Prompt engineering  
- In-context learning  
- Retrieval-Augmented Generation (RAG)

---

### Hands-on Notebook
**File:** `Karyashala_HandsOn.ipynb`  
Practical implementations for:

- Tokenization experiments  
- Embedding generation & similarity  
- Attention visualization  
- Zero/one/few-shot prompting  
- Basic RAG pipeline  


---

## Learning Objectives

By the end of this hands-on session, participants will be able to:

- Understand the LLM processing pipeline  
- Explain tokenization and embedding behavior  
- Interpret self-attention patterns  
- Apply prompt engineering techniques  
- Compare zero-shot, one-shot, and few-shot learning  
- Build a simple RAG system  
- Analyze grounded vs non-grounded generation  

---

## Requirements

Install dependencies before running the notebook:

```
pip install transformers accelerate sentencepiece torch
pip install sentence-transformers faiss-cpu
```

Recommended: Use GPU runtime in Colab for faster execution.

---

## How to Run

### 1️⃣ Clone the repository

```
git clone <repo-url>
cd <repo-folder>
```

### Open the notebook

- Upload to Google Colab, or  
- Run locally in Jupyter

### 3Execute cells sequentially

---

## Topics Covered

- Tokenization fundamentals  
- Embedding space intuition  
- Self-attention & multi-head attention  
- Prompt engineering  
- In-context learning (ICL)  
- Retrieval-Augmented Generation (RAG)

---

## Intended Audience

- NLP beginners  
- ML practitioners  
- Research scholars  
- Conversational AI developers  
- Healthcare AI enthusiasts  

---

## Notes

- Outputs may vary due to model stochasticity.  
- Examples use lightweight models suitable for Colab.  
- RAG demo uses FAISS for vector retrieval.

---

## Acknowledgement

Prepared for the **ANRF-PAIR Sponsored Karyashala — GenAI-Health 2026**.

---

## Contact

**Darshna Parmar**  
darshna.parmar@iiitvadodara.ac.in  

For issues or suggestions, please open a GitHub issue.
