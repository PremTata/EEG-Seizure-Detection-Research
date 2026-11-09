# EEG Seizure Detection Research

### Advanced AI and Graph Neural Network Approaches for Clinical EEG Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-orange.svg)](https://colab.research.google.com/)
[![Research](https://img.shields.io/badge/Domain-Healthcare%20AI-green.svg)]()

## About This Repository

This repository presents a collection of computational research implementations focused on AI-driven epileptic seizure detection and localization using clinical Electroencephalogram (EEG) signals.

It contains three research notebooks, each supporting a distinct research contribution:

1. Systematic benchmarking of deep learning models on highly imbalanced clinical EEG datasets.
2. Spatial Graph Convolutional Networks (Spatial-GCN) using functional connectivity for robust seizure screening.
3. Hybrid Dual-Stream Graph Attention for addressing the stability-plasticity dilemma in seizure localization.

The research explores machine learning, deep learning, functional connectivity, graph neural networks, and advanced attention mechanisms to investigate reliable AI-based neurological screening approaches.

## Research Portfolio

### Research 01: Deep Learning Benchmarking

**Notebook:** `1_Benchmarks-2.ipynb`

**Research Paper:**

Beyond the Accuracy Trap: A Systematic Benchmark of Deep Learning Vulnerabilities in Highly Imbalanced Clinical EEG

- Conference: International Conference on Computing Systems and Intelligent Applications (ComSIA-2026)
- Publisher: Springer Nature Switzerland
- Publication Status: Published
- DOI: https://doi.org/10.1007/978-3-032-30954-9_46

**Research Focus:**
- Clinical EEG preprocessing and segmentation.
- Machine learning and deep learning benchmarking.
- Performance evaluation under severe class imbalance.
- Investigation of the limitations of accuracy-based evaluation.
- Sensitivity, specificity, precision and F1-score analysis.

### Research 02: Spatial-GCN and Functional Connectivity

**Notebook:** `2_SpatialGCN.ipynb`

**Research Paper:**

Spatial-GCN with Functional Connectivity for Robust Seizure Screening in Imbalanced Clinical EEG

- Conference: 3rd IEEE International Conference on Advanced Computing Technologies (ICACT 2026)
- Paper ID: 666684
- Publisher: IEEE
- Publication Status: Published in IEEE Xplore
- DOI: https://doi.org/10.1109/ICACT70625.2026.11748713

**Research Focus:**
- EEG channel representation using graph structures.
- Functional connectivity analysis.
- Spatial Graph Convolutional Networks.
- Graph-based seizure screening.
- Robust evaluation on imbalanced EEG datasets.

### Research 03: Hybrid Dual-Stream Graph Attention

**Notebook:** `3_Hybrid_SOTA-2.ipynb`

**Research Paper:**

Resolving the Stability-Plasticity Dilemma in Seizure Localization via Hybrid Dual-Stream Graph Attention

- Research Area: Graph Neural Networks and Healthcare AI.
- Research Focus: Hybrid Dual-Stream Graph Attention.
- Objective: Investigating the stability-plasticity trade-off in EEG-based seizure localization.
- Publication Status: Manuscript ready for submission.

**Research Focus:**
- Hybrid graph attention architecture.
- Dual-stream representation learning.
- Stability-plasticity trade-off.
- EEG-based seizure localization.
- Experimental benchmarking against relevant state-of-the-art methods.

*This manuscript is a work in progress and has not yet been submitted or published.*

## Research Progression

The three research contributions follow a progressive research direction:

1. **Benchmarking:** Understanding deep learning vulnerabilities in highly imbalanced clinical EEG.
2. **Graph Learning:** Exploring spatial relationships and functional connectivity for robust seizure screening.
3. **Hybrid Attention:** Investigating advanced graph attention architectures for seizure localization.

## Technologies and Frameworks

- Python
- Google Colab
- MNE-Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Graph Neural Networks
- Matplotlib

## Research Evaluation Metrics

Depending on the experiment, the implementations investigate:

- Accuracy
- Precision
- Recall / Sensitivity
- Specificity
- F1-Score
- Confusion Matrix
- ROC-AUC

## Future Research Directions

- Patient-independent seizure detection and localization.
- Explainable Artificial Intelligence (XAI).
- Generalization across clinical EEG datasets.
- Robust and adaptive Graph Neural Networks.
- Clinical validation of AI-driven seizure screening systems.

## Researcher

**T. Prem Kumar**  
Assistant Professor  
Department of Computer Science and Engineering

**Research Interests:**
- Artificial Intelligence in Healthcare
- Biomedical Signal Processing
- Deep Learning
- Graph Neural Networks
- EEG-Based Seizure Detection and Localization

## Publications

1. Springer Nature: https://doi.org/10.1007/978-3-032-30954-9_46
2. IEEE Xplore: https://doi.org/10.1109/ICACT70625.2026.11748713

## Disclaimer

This repository is intended for academic and research purposes. The implementations are not intended for clinical diagnosis or direct medical decision-making.

## Acknowledgements

The research acknowledges the publicly available EEG datasets, open-source scientific libraries, and computational resources supporting these research experiments.
