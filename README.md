# Hybrid Cryptographic Algorithm with Statistical Analysis

This repository contains the implementation and evaluation of a hybrid cryptographic algorithm. The algorithm integrates multiple classical ciphers to enhance encryption strength and protect sensitive information from cryptanalytic techniques. Statistical analysis tools are included to evaluate and validate the algorithm's effectiveness.

---

## Overview

The hybrid cryptographic algorithm combines five classical ciphers:
- **Vigenère Cipher:** A polyalphabetic substitution cipher using a key to shift characters.
- **Columnar Transposition Cipher:** A transposition cipher rearranging plaintext based on a key.
- **Affine Cipher:** A substitution cipher employing mathematical transformations for encryption.
- **Rail Fence Cipher:** A transposition cipher organising text into a zigzag pattern.
- **Playfair Cipher:** A digraph substitution cipher encrypting pairs of letters.

The combined hybrid approach leverages the strengths of these individual ciphers to produce a robust encryption algorithm resistant to common cryptanalytic attacks.

---

## Features

- **Multi-layered Encryption:** Integrates five classical ciphers into a single encryption function.
- **Statistical Evaluation:** Includes tools for frequency analysis, chi-square testing, entropy calculation, and Index of Coincidence (IC).
- **Visualisation Capabilities:** Generates comparative graphs for plaintext and ciphertext frequency distributions, entropy, and IC values.

---

## Requirements

Ensure the following are installed:
- Python 3.x
- Jupyter Notebook (if using the notebook files)
- Libraries:
  - `matplotlib`: For creating visualisations.
  - `pandas`: For organising and analysing data.
  - `numpy`: For numerical operations.
  - `scipy`: For statistical calculations.

---

## Installation

1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
