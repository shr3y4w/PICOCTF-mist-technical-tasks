## RSA

RSA is a symmetric cryptographic algorithm, which means it works with a public and private key. The public key is published, while thr private key is kept private. Both are based on two prime numbers, eg. p and q, which should be kept hidden. The public key is made by multiplying the two prime numbers *(n=p\*q)* and an exponent e *(1 < e < Φ(n))*, where *Φ(n)=(p-1)(q-1)*

#### Encryption:
*Encrypted data c = (89\*\*e)mod n*
