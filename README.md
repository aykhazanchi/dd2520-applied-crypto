# dd2520-applied-crypto

### Tiny AES

A tiny AES implementation in Python done as part of the DD2520 Applied Cryptography course at KTH Royal Institute of Technology. This implements AES in Electronic Code Block (ECB) mode and was done to understand how AES works on a lower level.

### Input / Output
- The data is read as stdin in bytes and the output is in bytes as well. This is mostly for the validations to run on Kattis. 
- The first 16 bytes of the input are the key and the rest is considered the message to be encrypted.
