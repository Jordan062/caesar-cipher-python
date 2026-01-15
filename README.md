# caesar-cipher-python
A Python implementation of the Caesar Cipher algorithm for text encryption and decryption, featuring input validation and case-preservation.

# Caesar Cipher Tool

A Python script that implements the classic Caesar Cipher, allowing users to encrypt and decrypt messages by shifting characters in the alphabet.

## Technical Highlights
- [cite_start]**Bidirectional Logic:** Uses a single core function (`caesar`) to handle both encryption and decryption by toggling a boolean flag[cite: 1, 3].
- [cite_start]**Advanced String Mapping:** Implements `str.maketrans` and `text.translate` for efficient character replacement[cite: 3].
- [cite_start]**Input Validation:** Includes strict checks to ensure the shift value is an integer between 1 and 25[cite: 1, 2].
- [cite_start]**Case Sensitivity:** Properly handles both uppercase and lowercase letters while maintaining non-alphabetic characters[cite: 3].

## How to Use
The script provides two main helper functions:

```python
# To encrypt a message
[cite_start]encrypted = encrypt('freeCodeCamp', 3) # Returns 'iuhhFrghFdps' [cite: 3]

# To decrypt a message
[cite_start]decrypted = decrypt('iuhhFrghFdps', 3) # Returns 'freeCodeCamp' [cite: 3

Author
Developed by Raullysson Jordan as part of the freeCodeCamp Python curriculum.
