# Crypto-Project
This repository contains my project in cryptography created during my course work. It is written in C-program.

## Problem Statement

    1. Consider the prime number p = 10007.

    2. Consider the generator g = 5 of the cyclic group Z∗p with the standard multiplication modulo p. Here Z∗(p) = {1, 2, ..., p−1}.

    3. Consider two users: Alice and Bob.

    4. Using Diffie-Hellman key exchange protocol on the above mentioned group (Z∗p, × mod p), Alice and Bob will establish a common secret key of 128-bit length.

    5. Program will ask for secret keys of Alice and Bob.

    6. After giving these inputs, common secret key of Alice (say K(A)) and Bob (say K(B)) will be displayed as output.

    7. Program will ask for Alice’s 128-bit message (say M(A)). Input will be 16 separate bytes in hexadecimal. As for example : M(A) = 00 11 22 33 44 55 66 77 88 99 aa bb cc dd ee ff.

    8. Alice will encrypt the given message (M(A)) using AES-128 bit encryption algorithm with her
    key KA. Let the generated ciphertext be C(A). i.e., C(A) = EncAES-128(M(A), K(A)).

    9. Alice will generate a MAC for MA using the describe algorithm. The description of MAC is
    MAC(A) = (M(A) ⊕ K(A)).

    10. Your program will display the ciphertext C(A) and MAC(A).

    11. Alice will pass ciphertext C(A) and MAC(A) to Bob. This will be passed inside your code.

    12. Bob will decrypt C(A) using AES-128 bit decryption algorithm with his key K(B). Let the decrypted text be M(B). i.e., M(B) = DecAES-128(C(A), K(B)).

    13. Bob will generate MAC(B) = (M(B) ⊕ K(B)).

    14. Your program will display M(B) and MAC(B). 

    If the code is correct then M(A) = M(B) and MAC(A) = MAC(B).

