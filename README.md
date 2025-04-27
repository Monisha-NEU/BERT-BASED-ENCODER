# BERT-Based News Classification with SVC

Fine-tuned BERT-base-uncased on the AG News dataset to classify news articles into four categories.  
Extracted embeddings from the fine-tuned BERT model and trained a Linear Support Vector Classifier (SVC) for final classification.

---

## Project Overview

- **Model Fine-Tuning**:  
  Fine-tuned the `BERT-base-uncased` model to learn contextual representations of news articles from the **AG News dataset**.

- **Feature Extraction and Classification**:  
  - Extracted dense vector embeddings from the BERT model.
  - Trained a **Linear Support Vector Classifier (SVC)** using the extracted embeddings.

- **Preprocessing Techniques**:
  - Implemented **tokenization**, **padding**, and **attention masks** to ensure uniform sequence lengths and effective attention learning.

- **Performance**:
  - Achieved **96.4% training accuracy**.
  - Achieved **89.4% testing accuracy**.

---

## Tech Stack

- Python
- PyTorch
- Transformers (Hugging Face)
- Scikit-learn (SVC Classifier)
- AG News Dataset

---
