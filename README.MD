# Network Intrusion Detection — Attack Classification

## Overview

A machine learning model that classifies network traffic events by attack
type (DDoS, Malware, Intrusion), mirroring real SOC intrusion detection systems.

## Dataset

- Source: Github — Cybersecurity Attacks Dataset [https://github.com/incribo-inc/cybersecurity_attacks]
- 40,000 rows, 25 features
- Target: Attack Type (multiclass)
- This data set is heavily normalized and cleaned before, which reduces the presence of typical real-world patterns such as class imbalance, clustering, or temporal spikes.



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



## How to Run

pip install -r requirements.txt
jupyter notebook notebooks/cybersecurity_analysis.ipynb

## Tech Stack

Python · pandas · scikit-learn · seaborn · matplotlib
