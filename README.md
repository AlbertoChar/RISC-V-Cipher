# RISC-V-Cipher

**Introduction**

This project aims to provide basic encryption and decryption functionalities using simple algorithms. The algorithms implemented here include:

Caesar cipher: A substitution cipher where each character in the plaintext is shifted by a fixed number of positions down the alphabet.
Block cipher: A cipher that operates on blocks of characters instead of individual characters.
Dictionary cipher: A substitution cipher that replaces characters with their corresponding positions in the alphabet or vice versa.
Frequency analysis: A technique to determine the most likely decryption key based on the frequency of characters in the ciphertext.
Usage

To use the encryption and decryption functions, follow the steps below:

Place the plaintext you want to encrypt in the .data section with the label myplaintext.
Define any additional data required for the algorithms, such as keys or substitution tables.
Call the callerLoop function in the .text section to run the encryption algorithms.
To decrypt the ciphertext, call the decipheringLoopCaller function instead.
Please make sure to follow the comments in the code to understand the usage of specific functions and their requirements.

**Algorithms**

Caesar Cipher
The cesareChar function implements the Caesar cipher encryption for both uppercase and lowercase characters.

Block Cipher
The blocchiCipher function performs block cipher encryption by combining characters from the plaintext with characters from the key.

Dictionary Cipher
The dizionarioCipher function substitutes characters in the plaintext with their corresponding positions in the alphabet or vice versa.

Frequency Analysis
The occorrenzeFunc function analyzes the frequency of characters in the ciphertext to help decipher the message.
