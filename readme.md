# Drone localization and DOA estimation

This repository contains the source code used in the experiments of the doctoral thesis titled:

**"Acoustic-based Drone Localization and DOA Estimation in Highly Noisy Environments"**

Author: Rigel Procópio Fernandes  
Institution: Programa de Pós-Graduação em Engenharia de Defesa (PGED) – Instituto Militar de Engenharia (IME)  
Defense Date: July 4, 2025

## Abstract

The thesis proposes and evaluates multiple methods for estimating the Direction of Arrival (DOA) and localization of drones based on their acoustic emissions. This is particularly relevant for scenarios where traditional RF or visual detection systems may fail, such as in low-visibility conditions or when drones operate without active communication signals. Key contributions include:
- A robust DOA estimator using the **Zero Cyclic Sum (ZCS)** condition.
- An enhanced solution with **Least Squares (LS)** post-processing.
- A heuristic approach using **Genetic Algorithms (GA)** to reduce computational complexity.
- Exhaustive Search with optimized methods to include secodary peaks to enhance **localization** results, including a comparative evaluation with a **Neural Network** model for TDOA-based localization.
