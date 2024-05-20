# rungle

This repository contains a simple encryption and decryption tool written in Python. The tool uses a basic algorithm to encode and decode messages using a provided key. This can be useful for CTF (Capture The Flag) challenges or educational purposes.


- `crypto.py`: The main script containing the encryption and decryption functions.


1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. Run the `crypto.py` script:
    ```sh
    python crypto.py
    ```

3. Modify the `message` and `key` variables in `crypto.py` to encrypt and decrypt your own messages.


In the `crypto.py` script, you can see the following example:

```python
message = "This is a secret message."
key = "simplekey"

encrypted = encrypt(message, key)
decrypted = decrypt(encrypted, key)

print(f"Original: {message}")
print(f"Encrypted: {encrypted}")
print(f"Decrypted: {decrypted}")
