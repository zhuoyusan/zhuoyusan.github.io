---
title: "Evaluating MGT Detector Bias: Native vs Non-Native English Authors"
excerpt: "Investigating whether machine-generated text detectors exhibit systematic bias against non-native English speakers in scientific writing."
collection: portfolio
---

**Lab:** Ubiquitous Knowledge Processing Lab (UKP), TU Darmstadt
**Period:** December 2025 – April 2026
**Supervisor:** Prof. Rozovskaya

## Overview

This project investigates whether machine-generated text (MGT) detectors exhibit systematic bias against non-native English speakers (NNES) in scientific writing, and how LLM assistance, prompt language (L1 vs. L2), and model choice jointly shape this bias.

## Contributions

- Constructed two benchmarks: an essay-writing benchmark and a scientific-writing benchmark built from the ACL Anthology with venue-based filtering and native language identification to assign NNES/NES labels
- Designed an LLM-based augmentation pipeline that rewrites text at controlled proportions using multiple LLMs (LLaMA, T5) with prompts in different languages (L1 vs. L2), enabling systematic analysis of how editing degree, model choice, and prompt language affect detector bias
- Evaluated multiple detector families and measured group-wise fairness metrics across NNES and NES groups under varying levels of LLM modification
- Planned evaluation of data-centric bias mitigation strategies—including resampling, counterfactual data augmentation, and group-specific threshold optimization—to quantify fairness–utility trade-offs for MGT detection
