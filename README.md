# RSA FACTORING CHALLENGE
RSA (Rivest-Shamir-Adleman) is a widely used public-key cryptosystem that relies on the mathematical difficulty of factoring large composite numbers into their prime factors. RSA factoring is the process of determining the prime factors of the modulus used in an RSA encryption key pair. To understand this, let's break it down:

### 1. Public-Key Cryptosystem:
In a public-key cryptosystem like RSA, there are two keys: a public key and a private key. The public key is used for encryption, and the private key is used for decryption. The security of the system relies on the fact that it should be computationally infeasible to derive the private key from the public key.

### 2. Modulus and Prime Factors:
In RSA, the public key consists of a modulus (n) and an encryption exponent (e). The security of RSA is based on the difficulty of factoring the modulus (n) into its two prime factors (p and q). The private key contains the prime factors, so if someone can factor n, they can derive the private key and decrypt messages.

### 3. RSA Factoring:
RSA factoring is the process of finding the prime factors (p and q) of the modulus (n) from a given public key. This is a computationally intensive task because as the size of the modulus (n) increases, it becomes exponentially more difficult to factor it. The security of RSA relies on the belief that factoring large numbers into their prime components is a time-consuming task, even with the most powerful computers available.

This project aims at writing a factorize function to implement the RSA challenge.

## Author
Edozie Victor
