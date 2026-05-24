# Network Intrusion Detection — Attack Classification

## Overview

A machine learning model that classifies network traffic events by attack
type (DDoS, Malware, Intrusion), mirroring real SOC intrusion detection systems.

## Dataset

- Source: Kaggle — Cybersecurity Attacks Dataset
- 40,000 rows, 25 features
- Target: Attack Type (multiclass)

## Approach

- EDA → Preprocessing → Random Forest + Logistic Regression
- Evaluated with F1-score and confusion matrix

## Results

| Model               | Accuracy | F1 (macro) |
| ------------------- | -------- | ---------- |
| Logistic Regression | xx%      | xx         |
| Random Forest       | xx%      | xx         |

## Key Findings

- [e.g. "Packet length and protocol type were the strongest predictors"]
- [e.g. "DDoS was easiest to classify; Malware had most false negatives"]

## Real-World Relevance

[Connect to SIEM tools, IDS systems like Snort/Suricata — 2 sentences]

## How to Run

pip install -r requirements.txt
jupyter notebook notebooks/cybersecurity_analysis.ipynb

## Tech Stack

Python · pandas · scikit-learn · seaborn · matplotlib
