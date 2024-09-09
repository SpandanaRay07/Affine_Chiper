# Affine_Chiper
Encryption and Decryption software
This project implements the Affine Cipher, a type of substitution cipher, in Java. The cipher uses two keys, a multiplicative key (k1) and an additive key (k2), to encrypt and decrypt messages.
Features:
•	Encryption:
C=(P×k1+k2)mod  26C = (P \times k1 + k2) \mod 26C=(P×k1+k2)mod26
Encrypts each character based on its position in the alphabet.
•	Decryption:
P=((C−k2)×k1−1)mod  26P = ((C - k2) \times k1^{-1}) \mod 26P=((C−k2)×k1−1)mod26
Decrypts using the modular inverse of k1.
This project is useful for understanding the foundation of cryptography.
