---
title: "Endi-QM: Energy Efficiency via Intelligent In-Process Quality Monitoring"
excerpt: "Applying deep learning and reinforcement learning to industrial sensor data for product quality prediction and machine parameter optimization."
collection: portfolio
---

**Lab:** Produktionsmanagement, Technologie und Werkzeugmaschinen Lab (PTW), TU Darmstadt
**Period:** November 2022 – June 2024

## Overview

Endi-QM applies deep learning and reinforcement learning methods to industrial sensor data and machine configuration parameters to predict product quality and optimize machine settings — reducing trial-and-error in manufacturing processes.

## Contributions

- Developed an advanced program integrating a deep learning model (PyTorch) and actor-critic models (Stable-Baseline3) to optimize machine parameters and achieve desired product quality from initial machine and sensor data
- Customized a reinforcement learning environment via OpenAI Gym for this specific industrial task
- Conducted evaluations showing the trained agent iteratively adjusts parameters across various datasets, achieving desired product quality within 10 steps
- Explored multimodal fusion strategies to enhance classification performance across sensor modalities
- Refactored a GNN-based solution with GNNExplainer for interpretable model predictions
- Utilized Hydra + OmegaConf for efficient experiment configuration management
- Tracked experiments with MLFlow and TensorBoard for reproducibility and transparency
- Ensured compatibility with diverse industrial datasets including LEGO products and AUDI welding data
