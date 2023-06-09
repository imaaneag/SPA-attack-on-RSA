# SPA-attack-on-RSA

Here is the link to the video implementation : https://drive.google.com/file/d/1jdvwYNNSVNsVhR463yQlQ3TYOrbUEQR2/view?usp=sharing

 Cryptography is a science that studies secure communication methods in the presence of adversaries who seek to intercept or alter exchanged information. It relies on mathematical algorithms that allow messages to be encrypted and decrypted using a secret key. Cryptography ensures the confidentiality, authenticity, and integrity of data and is used in many fields such as computer security, wireless communication, online banking, e-commerce, etc.

Symmetric cryptography (also known as secret key cryptography) and asymmetric cryptography (also known as public key cryptography) are two types of cryptography. The former allows messages to be encrypted and decrypted using the same shared secret key between the two communicating parties, while the latter involves each communicating party having a public key known by everyone and a secret private key, one for encryption and the other for decryption.

RSA (Rivest-Shamir-Adleman), which is part of asymmetric cryptography, is one of the most popular cryptography algorithms used to secure electronic communications. It is based on the difficulty of factoring very large integers into their prime factors, which makes finding the private key very difficult for an adversary. However, even the most robust cryptography algorithms can be vulnerable to attacks if their implementation is not secure. The SPA attack on RSA is one of these attacks that aims to exploit power leaks in hardware implementations of RSA to recover the private key. This attack illustrates the importance of implementation security in cryptography and highlights the need for physical and logical protection measures to secure cryptography devices.

In this document, we will first discover the principle of RSA, and then how the SPA attack exploits modular exponentiation to break RSA. Secondly, we will present a simulation of this attack on a physical device.
