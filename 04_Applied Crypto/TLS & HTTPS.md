## What is TLS?
- TLS (Transport Layer Security) is a protocol for encrypting data over a network.
- HTTPS is HTTP over TLS.

## TLS Handshake Overview
1. **Client Hello**: Includes supported TLS versions and cipher suites.
2. **Server Hello**: Sends back its digital certificate and selected cipher.
3. **Certificate Validation**: Client checks the server’s certificate (CA signature).
4. **Key Exchange**: Session key is securely established using asymmetric encryption.
5. **Symmetric Encryption Begins**: The session is encrypted using the session key.

## Why TLS Matters
- Provides **Confidentiality**, **Integrity**, and **Authentication**.
- Ensures protection against man-in-the-middle (MITM) attacks.

## Certificate Validation Steps
- Check expiration date.
- Check signature by a trusted CA.
- Check CRL/OCSP to ensure it hasn’t been revoked.
