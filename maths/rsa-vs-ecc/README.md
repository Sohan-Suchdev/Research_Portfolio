# Comparative Analysis: RSA vs. Elliptic Curve Cryptography

### Abstract
This paper contrasts the mathematical foundations and computational efficiency of RSA encryption against Elliptic Curve Cryptography (ECC). The study evaluates the security-to-performance ratio of Integer Factorization (RSA) versus the Elliptic Curve Discrete Logarithm Problem (ECC).

### Key Investigations
* **Number Theory:** Analysis of Modular Arithmetic, Euler's Totient Theorem, and Finite Fields ($\mathbb{F}_{p}$).
* **Group Laws:** Examination of Abelian group properties on elliptic curves, including point addition and doubling protocols.
* **Algorithmic Complexity:**
    * **RSA:** Derived time complexity of $O(n^2)$ for encryption and $O(n^3)$ for decryption.
    * **ECC:** Derived time complexity of $O((\log k)^2)$ for point multiplication.
* **Quantum Computing:** Evaluation of **Shor’s Algorithm** and its implications for prime factorisation in polynomial time.

### Conclusion
The analysis confirms that ECC offers superior efficiency, requiring significantly smaller key sizes (256-bit) to match the security of much larger RSA keys (3072-bit), making it ideal for resource-constrained environments.

### View the Research
[Download Paper (PDF)](./rsa-vs-ecc-cryptography.pdf)
