# COVID19-Vaccine-Misinformation-Analysis
Thesis 

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.9%2B-red)
![Transformers](https://img.shields.io/badge/Transformers-4.12%2B-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

An integrated Natural Language Processing (NLP) and Network Analysis pipeline for detecting and analyzing COVID-19 vaccine misinformation on Twitter. This repository contains the complete implementation for my Master's Thesis: **"Bridging the Gap: An Integrated NLP-Network Analysis of COVID-19 Vaccine Misinformation"**.

## 🔬 Research Overview

This research addresses a critical gap in misinformation studies by developing a comprehensive methodology that integrates:

- **🤖 Transformer-based NLP Classification** - Fine-tuned BERT models for misinformation detection
- **🕸️ Network Analysis** - Diffusion patterns and community structure mapping
- **📊 Integrated Analysis** - Connecting linguistic features to diffusion behavior

### Key Finding: The Volume-Quality Paradox

Our analysis revealed a **Volume-Quality Paradox**: while misinformation dominates by volume (96.6% in our sampled discourse), reliable content demonstrates superior engagement quality with a **45% higher viral rate** (8.0% vs 5.5%).

## 🏆 Key Results

| Metric | Performance | Significance |
|--------|-------------|--------------|
| **Classification Accuracy** | 91.44% (DistilBERT) | State-of-the-art misinformation detection |
| **Network Scale** | 10,675 nodes, 19,771 edges | Comprehensive discourse mapping |
| **Echo Chamber Effect** | Assortativity = 0.063 | Quantitative evidence of homophily |
| **Emotion-Diffusion Correlation** | r = 0.63 (p < 0.01) | Strong link between negative emotion and misinformation spread |

## 🗂️ Repository Structure

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- pip or conda

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/COVID19-Vaccine-Misinformation-Analysis.git
   cd COVID19-Vaccine-Misinformation-Analysis
   pip install -r requirements.txt
