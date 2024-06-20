# OWN JWT token

__JWT__ stands for __JSON Web Token__.

### Process
1. Hashing: Hashing is a process where we use a special mathematical formula (called a hash function) to convert any amount of data into a fixed-size string of characters. This string, known as a hash or digest, uniquely represents the original data.
2. Symmetric Encryption: We'll encrypt the header and payload using a symmetric encryption algorithm.
3. Signing: We'll sign the JWT using asymmetric encryption (RSA) to ensure authenticity and integrity.

### Steps
1. take JS object as payload
2. convert JS payload to JSON object
3. Hashing the Payload

