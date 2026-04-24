# Cryptography-Analysis-Project
Cryptanalysis of Caesar and Simple Substitution Ciphers using Python
This project was completed for the Elements of Data Security course at the University of Bologna
#overview: This repository contains Python implementations for attacking two historical cryptosystems:
1-Caesar Cipher: Broken via a Brute-Force attack. We successfully decrypted the text on the 18th attempt with a shift of 18
2-Simple Substitution Cipher: Broken via Frequency Analysis. By analyzing the frequency of characters in the ciphertext and comparing them to English letter distributions, we retrieved the plaintext.
#Contents:
-QuantumResisters.ipynb: Full Jupyter Notebook containing Python functions for caesar_decrypt, letter_distribution, and substitution_decrypt
-letter_distribution.pkl: A serialized dictionary containing the probability values used for the frequency attack.
-ciphertext_simple.txt: The encrypted text describing the history of substitution ciphers.
