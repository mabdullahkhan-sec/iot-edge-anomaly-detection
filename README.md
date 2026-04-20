# IoT Edge Anomaly Detection

A research project evaluating and comparing two unsupervised machine learning models for anomaly detection in **resource-constrained IoT edge environments**, using the **CIC IoT - DIAD 2024 Dataset**.

---

## Overview

| Detail | Info |
|---|---|
| Author | Muhammad Abdullah Khan |
| Dataset | CIC IoT - DIAD 2024 |
| Models Compared | Isolation Forest vs Robust Random Cut Forest (RRCF) |
| Focus | Anomaly detection reliability on IoT edge devices |

---

## Problem Statement

IoT edge devices operate under strict resource constraints limited CPU, memory, and power making traditional security monitoring approaches impractical. Unsupervised anomaly detection models offer a lightweight alternative, but their reliability and stability across varying contamination levels must be carefully evaluated before deployment.

---

## Models Compared

### Isolation Forest
- Tree-based unsupervised anomaly detection algorithm
- Isolates anomalies by randomly partitioning feature space
- Evaluated for F1-score stability across contamination levels

### Robust Random Cut Forest (RRCF)
- Streaming-compatible anomaly detection algorithm
- Designed for dynamic, real-time data environments
- Evaluated for adaptability and detection reliability

---

## Key Findings

- Compared model performance using **F1-score stability** across multiple contamination levels
- Analyzed trade-offs between detection reliability and computational overhead
- Assessed suitability for deployment on resource-constrained IoT edge nodes
- Provided recommendations for anomaly detection model selection in IoT security contexts

---

## Dataset

**CIC IoT – DIAD 2024**
- Source: Canadian Institute for Cybersecurity
- Contains labeled IoT network traffic for anomaly detection research

---

## Topics Covered

- Unsupervised machine learning for security
- Anomaly detection in IoT environments
- Edge computing security
- Model evaluation metrics (F1-score, precision, recall)
- Resource-constrained deployment considerations

---

## Files

| File | Description |
|---|---|
| `IoT_Edge_Anomaly_Detection.pdf` | Full research paper |

---

*Research Project · Muhammad Abdullah Khan · 2024–2025*
