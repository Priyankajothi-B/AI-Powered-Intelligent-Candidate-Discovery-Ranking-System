# AI-Powered-Intelligent-Candidate-Discovery-Ranking-System

## Overview

This project was developed for the Redrob AI Intelligent Candidate Discovery & Ranking Hackathon.

The objective is to recommend the Top-100 candidates for a Senior AI Engineer role from a dataset containing 100,000 candidate profiles.

Instead of relying only on keyword matching, this solution combines semantic understanding, recruiter-inspired scoring, and behavioural signals to rank candidates more like a human recruiter.

---

## Pipeline

Job Description

↓

Sentence Transformer Embedding

↓

Candidate Embeddings

↓

Semantic Similarity

↓

Recruiter Scoring

↓

Human-style Reranking

↓

Top 100 Candidates

↓

submission.csv

---

## Technologies

- Python
- Sentence Transformers
- Transformers
- PyTorch
- Pandas
- NumPy
- Scikit-learn

---

## Output

submission.csv containing

- candidate_id
- rank
- score
- reasoning
