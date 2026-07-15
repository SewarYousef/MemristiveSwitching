# Memristive Switching Optimization — Neural Network & Genetic Algorithm
**Research conducted at Argonne National Laboratory | Lemont, Illinois**

---

## Overview

Memristive devices are next-generation hardware components used in neuromorphic computing and energy-efficient memory systems. A key challenge in operating these devices is **minimizing Joule heat losses** during resistive switching — excess heat degrades performance and shortens device lifespan.

This project tackles that problem using a two-stage machine learning pipeline:

1. **A deep learning Neural Network** trained to approximate the switching behavior of a physical memristive device
2. **A Genetic Algorithm** that automatically optimizes the neural network's weights across multiple generations to minimize loss — replacing manual hyperparameter tuning with evolutionary computation

Both models were validated against **real hardware benchmarks at Argonne National Laboratory**, making this an end-to-end applied ML project grounded in experimental physics data.

---

## Results

| Metric | Value |
|---|---|
| Neural Network approximation accuracy | **90%** against hardware benchmarks |
| Loss reduction via Genetic Algorithm | **10% improvement** over baseline after 3 generations |
| Optimization approach | Evolutionary computation (GA) replacing manual tuning |

---

## Repository Structure

```
MemristiveSwitching/
│
├── NeuralNetworks_model_with_Joule_Loss.ipynb   # NN model trained on memristive hardware data
└── GeneticAlgorithm.ipynb                       # GA optimization of NN weights across generations
```

---

## Technical Stack

- **Language:** Python
- **ML Frameworks:** TensorFlow / PyTorch, NumPy, Matplotlib
- **Methods:** Deep Neural Networks, Genetic Algorithms, Hyperparameter Optimization, Time-Series Sensor Data Modeling
- **Environment:** Jupyter Notebook
- **Validation:** Physical hardware benchmarks at Argonne National Laboratory

---

## Why This Matters

This work sits at the intersection of **hardware-aware machine learning** and **energy-efficient computing** — two areas critical to the future of AI infrastructure. The techniques applied here (neural approximation of physical systems + evolutionary optimization) are directly transferable to:

- Predictive maintenance and remaining useful life (RUL) estimation in industrial systems
- IoT sensor data modeling
- Physics-informed machine learning

---

## About

This research was conducted as part of an ML internship at **Argonne National Laboratory** (U.S. Department of Energy), one of the nation's premier scientific research institutions.

**Researcher:** Sewar Dghaim
**Institution:** Argonne National Laboratory — Lemont, Illinois
**Period:** September 2024 – February 2025
