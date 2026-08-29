# Explainable Multi-Class Fake News Detection

An explainable NLP-based system for detecting and analyzing potentially misleading news. Unlike traditional binary fake-news classifiers, this project provides a **multi-class verdict, credibility score, supporting/contradicting evidence, and an explanation for the prediction**.

## Features

* **Text & URL Input** — Analyze pasted news text or directly provide a news article URL.
* **Multi-Class Classification** — Classifies content as:

  * Real
  * Fake
  * Misleading
  * Satire
  * Unverified
* **Credibility Score** — Provides a percentage-based credibility score instead of only a label.
* **Evidence Verification** — Retrieves relevant supporting or contradicting evidence for the claim.
* **Explainable Predictions** — Explains the key factors behind the model's verdict.
* **Unified Results** — Displays the verdict, credibility score, evidence, and explanation together.

## System Overview

```text
News Text / URL
       ↓
Article Extraction
       ↓
Text Preprocessing
       ↓
NLP / Classification Model
       ↓
 ┌─────┴─────────────┐
 ↓                   ↓
Verdict          Evidence Retrieval
 ↓                   ↓
Credibility      Supporting /
Score            Contradicting Evidence
 └─────────┬─────────┘
           ↓
      Explanation
```

## Objective

To build a **transparent and practical fake-news detection system** that goes beyond simply labeling content as fake or real, helping users understand **how credible a claim is, why it received its verdict, and what evidence supports or contradicts it**.


## Research Basis

This project extends existing NLP and deep-learning approaches to fake-news detection by addressing limitations such as **binary classification, lack of explainability, absence of evidence verification, and text-only input**.

## Project Status

🚧 **not yet started**
