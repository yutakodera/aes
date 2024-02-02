# Sample implementation of AES (Advanced Encryption Standard)

This repository provides a sample implementation of AES with Python 3.10.
It is not optimized for practical use for the sake of AES beginner's understanding.
In addition, since decryption can be implemented by making the inverse functions after one's understanding of the encryption, this repository also does not focus on it.

The state handled in the algorithm is expressed by a list of lists as follows:
```
state = [
  [s_00, s_01, s_02, s_03],
  [s_10, s_11, s_12, s_13],
  [s_20, s_21, s_22, s_23],
  [s_30, s_31, s_32, s_33]
]
```
