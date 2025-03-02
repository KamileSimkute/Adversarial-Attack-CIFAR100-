# Adversarial-Attack-CIFAR100-
This project uses Fast Gradient Sign Attack (FGSM) to expose neural network vulnerabilities. Tests on CIFAR-100 show accuracy drops with small perturbations, highlighting security risks. Findings stress the need for stronger defenses in deep learning.

# Adversarial Attacks using Fast Gradient Sign Attack (FGSM)

## Overview
Adversarial attacks mislead deep learning models by introducing small perturbations. One major risk is manipulating self-driving cars. This project explores Fast Gradient Sign Attack (FGSM), demonstrating how minimal input changes impact neural network predictions.

## Research Objective
This project examines deep learning model vulnerabilities, particularly in computer vision. The primary aim is to implement FGSM and analyse its effects.

## Methodology
The Fast Gradient Sign Attack (FGSM) is implemented using Python and PyTorch in PyCharm. The study explores adversarial learning techniques, generates adversarial examples, and visualizes accuracy vs. epsilon trends.

## Key Findings
- Using the CIFAR-100 dataset, accuracy decreases as epsilon increases, exposing model weaknesses.
- FGSM successfully generates adversarial examples, confirming deep learning models’ susceptibility.
- The results highlight the need for improved model defences.

## Conclusion
This study reveals how vulnerable neural networks are to adversarial attacks. Findings emphasize the need for robust training techniques to enhance AI security.
