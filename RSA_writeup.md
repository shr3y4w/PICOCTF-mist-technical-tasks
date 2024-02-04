## RSA

RSA is a symmetric cryptographic algorithm, which means it works with a public and private key. The public key is published, while thr private key is kept private. Both are based on two prime numbers, eg. p and q, which should be kept hidden. The public key is made by multiplying the two prime numbers *(n=p\*q)* and an exponent e *(1 < e < Φ(n))*, where *Φ(n)=(p-1)(q-1)*<br><br>

The private key is made by *d = (k\*Φ(n) + 1) / e*, for some value *k*.

### Encryption:
*Encrypted data c = (89\*\*e)mod n*

### Decryption:
*Decrypted Data = (c\*\*d)mod n*


### Vulnerabilities
* Data transfer rate is slow, especially for large amounts of data<br>
* Larger key sizes are ideal for higher security, which requires more storage space<br>
* vulnerable to side-channel attacks, where information leaked through side channels about power consumption, electromagnetic radiation, and timing analysis can be used by attackers to extract the private key.
 

