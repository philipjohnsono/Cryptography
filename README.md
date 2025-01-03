# Hybrid Cryptographic Algorithm with Statistical Analysis

This repository demonstrates the development and evaluation of a hybrid cryptographic algorithm. The algorithm integrates multiple classical ciphers to enhance encryption strength and protect sensitive data from cryptanalytic attacks. The hybrid approach leverages the Vigenère Cipher, Columnar Transposition Cipher, Affine Cipher, Rail Fence Cipher, and Playfair Cipher, applying them sequentially to create a robust encryption method.

---

## What This Repository Includes

1. **Hybrid Cryptographic Algorithm:**
   - Combines five classical ciphers into a single encryption function.
   - Sequentially applies substitution and transposition techniques to maximise encryption security.

2. **Statistical Analysis Tools:**
   - **Frequency Analysis:** Compares character distributions in plaintext and ciphertext.
   - **Chi-Square Test:** Measures deviations from expected frequency patterns in ciphertext.
   - **Entropy Calculation:** Evaluates randomness and unpredictability in ciphertext.
   - **Index of Coincidence (IC):** Analyses uniformity in character distributions to assess encryption strength.

3. **Visualisation:**
   - Frequency distribution charts for plaintext vs ciphertext.
   - Graphs and tables displaying statistical metrics such as entropy and IC.

---

## Key Highlights

### Encryption Process:
- The hybrid cryptographic function encrypts plaintext by combining the following ciphers:
  - Vigenère Cipher
  - Columnar Transposition Cipher
  - Affine Cipher
  - Rail Fence Cipher
  - Playfair Cipher
- A sample dataset (a 500-word cover letter) is used to demonstrate the encryption process and subsequent analysis.

### Statistical Evaluation:
- **Frequency Analysis:** Reveals disrupted natural language patterns in ciphertext.
- **Chi-Square Test:** Confirms significant deviations from natural letter frequencies.
- **Entropy Calculation:** Indicates increased randomness in ciphertext.
- **Index of Coincidence (IC):** Shows improved uniformity and reduced predictability in ciphertext distributions.

---

## Example Results

- **Plaintext Entropy:** 4.18
- **Ciphertext Entropy:** 4.52
- **Plaintext IC:** 0.055
- **Ciphertext IC:** 0.038

These results demonstrate the effectiveness of the hybrid algorithm in increasing randomness and reducing the predictability of the encrypted text, making it more resistant to cryptanalytic attacks.
