---
title: "WocaR-RL: Worst-case-aware Robust Reinforcement Learning"
excerpt: "A robust reinforcement learning framework that enhances AI policy resilience against adversarial attacks through worst-case value estimation and state importance weighting.<br/><img src='/files/wocar.png'>"
collection: portfolio
---

## WocaR-RL: Worst-case-aware Robust Reinforcement Learning

**Project Repository:** [https://github.com/jmunetong/wocar_project](https://github.com/jmunetong/wocar_project)

### Overview

A comprehensive robust reinforcement learning framework developed as part of Stanford University CS234 coursework. WocaR-RL addresses critical vulnerabilities in deep reinforcement learning policies by creating neural networks that maintain performance under adversarial perturbations and attacks.

### Key Features

- **Adversarial Robustness:** Advanced algorithms to handle minor perturbations and adversarial examples in RL environments
- **Worst-case Value Estimation:** Novel approach to evaluate and optimize for worst-case scenarios during policy learning
- **Multiple Algorithm Implementations:** Vanilla PPO, Robust PPO (R-PPO), and the innovative WocaR-RL PPO
- **State Importance Weighting:** Sophisticated technique to prioritize critical states during training
- **Attack-Resilient Policies:** Maintains performance across different attack scenarios without additional sample generation

### Technical Implementation

- **Languages:** Python 3.7+
- **Core Frameworks:** PyTorch 2.1.0, Gymnasium 0.29.1
- **Environment:** MuJoCo physics simulation (primarily Hopper-v4)
- **Key Techniques:** Convex relaxation, adversarial action space definition, robust policy optimization
- **Algorithm Focus:** Proximal Policy Optimization with robustness enhancements

### Research Impact

This Stanford CS234 project contributes to the critical field of AI safety by developing reinforcement learning algorithms that are inherently robust to adversarial conditions. The WocaR-RL framework represents a significant advancement in creating AI systems that can operate reliably in real-world scenarios where adversarial perturbations are possible, enhancing the practical deployment of RL-based systems.
