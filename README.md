# Exploring the Impact Mechanisms of EEG Signals and Emotional Intelligence on Language Learning Efficiency

This project explores how neural activity (EEG signals) and emotional intelligence interact to influence language learning efficiency. We propose a novel machine learning framework that dynamically adapts to learners' brain states and emotional cues to optimize learning outcomes.

## 🧠 Project Overview

Traditional language learning models often overlook the dynamic nature of cognitive and emotional processes. Our work introduces a personalized, adaptive framework that incorporates:

- **EEG-based neural signal modeling**
- **Emotion-aware learning strategies**
- **Adaptive content control for language learning tasks**

We design and evaluate a two-component system:

### 🔹 Context-Aware Relational Encoder (CARE)

An attention-driven encoder that models relational semantics from EEG input sequences, learning how learners mentally process language-related content.

### 🔹 Adaptive Contextual Enhancement (ACE)

A dynamic adaptation module that enhances content delivery in real time using:

- Meta-learning
- Reinforcement feedback
- Emotion- and cognition-informed data augmentation

## 🧪 Experimental Setup

- **Dataset Used:** AMIGOS (EEG + emotional context video dataset)
- **Modality:** Raw EEG sequences + emotional labels
- **Evaluation Metrics:** Classification accuracy, adaptability under emotional shifts
- **Benchmarks:** Compared against transformer-based and GRU-based baselines

> ⚠️ Note: While AMIGOS is not a direct language learning dataset, it provides emotionally rich and cognitively relevant EEG recordings suitable for simulating language learning dynamics.

## 📈 Key Findings

- Our model outperforms conventional architectures on tasks involving emotionally modulated neural input.
- CARE + ACE architecture shows improved generalization to variable affective-cognitive states.
- Demonstrates potential for personalized, neuroscience-driven educational systems.

## 📂 Project Structure

```bash
.
├── data/                 # Preprocessed EEG + emotion data
├── models/
│   ├── care.py           # CARE encoder module
│   └── ace.py            # ACE enhancement module
├── train/
│   ├── train_model.py    # Training script
│   └── eval_model.py     # Evaluation
├── utils/
│   └── preprocess.py     # EEG and emotion data preprocessing
├── figures/              # Paper figures (Fig.1, Fig.3)
└── README.md
