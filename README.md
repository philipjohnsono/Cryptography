# Hybrid Cryptographic Algorithm and Statistical Analysis

This repository contains the implementation and analysis of a hybrid cryptographic algorithm developed for my thesis. The algorithm combines multiple classical ciphers to enhance security and resist common cryptanalytic techniques. Statistical analyses were performed to evaluate the strength of the encryption.

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Usage](#usage)
5. [Statistical Analysis](#statistical-analysis)
6. [Contributing](#contributing)
7. [License](#license)

## Overview

The hybrid cryptographic algorithm integrates the following classical ciphers:
- **Vigenère Cipher**
- **Columnar Transposition Cipher**
- **Affine Cipher**
- **Rail Fence Cipher**
- **Playfair Cipher**

Statistical analyses, such as frequency analysis, chi-square testing, entropy calculation, and the Index of Coincidence (IC), are used to evaluate the ciphertext's strength.

## Features

- Combines multiple classical ciphers for enhanced encryption.
- Performs statistical analysis to measure encryption effectiveness.
- Provides tools for visualising results (e.g., frequency distribution charts).

## Requirements

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Libraries: `matplotlib`, `pandas`, `numpy`, `scipy`

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
