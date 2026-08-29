# Internship Feedback Sentiment Analysis

### Task 2 — Machine Learning Internship Project

An NLP-based machine learning project that analyzes internship/employee feedback and classifies it into three sentiment categories: **Negative, Neutral, and Positive**.

The project uses a fine-tuned **DistilBERT** transformer model and an interactive **Gradio** interface for sentiment prediction.

---

## 📌 Project Overview

Organizations collect large amounts of written feedback from interns and employees. Manually analyzing this feedback can be time-consuming.

This project uses Natural Language Processing (NLP) and transformer-based deep learning to automatically classify written feedback according to its sentiment.

### Objectives

- Analyze written internship/employee feedback
- Classify feedback into three sentiment categories
- Apply Natural Language Processing techniques
- Fine-tune a transformer-based model
- Evaluate model performance
- Provide an interactive sentiment prediction interface

---

## 🤖 Model

| Parameter | Value |
|---|---|
| Model | DistilBERT |
| Pre-trained Model | `distilbert-base-uncased` |
| Task | Text Classification |
| Classes | 3 |
| Maximum Sequence Length | 128 |
| Training Epochs | 3 |
| Learning Rate | `2e-5` |

---

## 🏷️ Sentiment Classes

| Class | Description |
|---|---|
| Negative | Negative feedback |
| Neutral | Neutral or mixed feedback |
| Positive | Positive feedback |

---

## 🔄 Machine Learning Pipeline

```text
Internship / Employee Feedback
              ↓
       Data Preparation
              ↓
         Tokenization
              ↓
           DistilBERT
              ↓
        Model Fine-Tuning
              ↓
           Evaluation
              ↓
      Sentiment Prediction
              ↓
        Gradio Interface
