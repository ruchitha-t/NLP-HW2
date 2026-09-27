# CS 5760 - Natural Language Processing
## Homework 2

- **Student Name:** Ruchitha Thavutu
- **Student ID:** 700778594

This repository contains the solutions and Python implementations for Homework 2 of CS 5760 - Natural Language Processing.

- Document classification using probability and Laplace smoothing
- Harms and fairness issues in NLP classification
- Bigram probabilities and zero-probability problems
- Backoff models
- Confusion matrix evaluation
- Bigram language modeling

The programming implementations are provided as Jupyter Notebook files.

---

## Files in This Repository

### 1. `Q5_3.ipynb`

This notebook implements the confusion matrix evaluation from Part I, Question 5.

The given confusion matrix contains three classes:

- Cat
- Dog
- Rabbit

The program calculates:

- Per-class Precision
- Per-class Recall
- Macro Precision
- Macro Recall
- Micro Precision
- Micro Recall

For each class, the program uses:

Precision = TP/TP+FP  

Recall = TP/TP+FN

Macro averaging calculates the average of the class-level values.

Micro averaging combines the true positives, false positives, and false negatives across all classes before calculating the metric.

---

### 2. `q2part2_bigram_model.ipynb`

This notebook implements a Bigram Language Model for Part II, Question 1.

The corpus used in the assignment is:

```text
<s> I love NLP </s>
<s> I love deep learning </s>
<s> deep learning is fun </s>
