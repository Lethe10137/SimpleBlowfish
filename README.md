1. Encryption.

Put any text in `key.txt`. 
Put the clean-text content in `data.txt`. (ASCII only)

run
```bash
FILE=data.txt python blowfish.py
```
Encrypted text is written into `encrypt.txt` and stdout.

2. Decryption.

Put encrypted text in `encrypt.txt`.

run
```bash
python blowfish.py
```

Decryption result is written into stdout.
