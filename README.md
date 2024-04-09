# Navam's Encryption Technique (NET)

## Installation

`pip install navam`

## Encryption

```python
from navam import encrypt
encrypt('path_to_file')
```

The encrypted file is stored as `encrypted.nvm`

## Decryption

```python
from navam import decrypt
decrypt('encrypted.nvm')
```

### NOTE

* NET encrypts a single file. So, consider zipping a folder you want to encrypt.  
* The encrypted file can be many times larger than the original file.
