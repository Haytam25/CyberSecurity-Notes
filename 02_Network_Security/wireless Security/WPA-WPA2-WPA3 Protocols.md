# WPA, WPA2, WPA3 Wireless Security Protocols

## WEP (Wired Equivalent Privacy)
- Weak and outdated.
- Uses static encryption keys.
- Vulnerable to IV (Initialization Vector) attacks.
- Should NEVER be used.

## WPA (Wi-Fi Protected Access)
- Improvement over WEP.
- Uses TKIP (Temporal Key Integrity Protocol).
- Still weak by modern standards.

## WPA2
- Introduced AES encryption (stronger than TKIP).
- Uses CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol).
- Still widely used today.

## WPA3
- Stronger encryption: 192-bit security.
- Uses **SAE (Simultaneous Authentication of Equals)** instead of PSK.
- Forward secrecy.
- Better defense against dictionary and brute-force attacks.

## Summary Table

| Protocol | Encryption | Key Management | Status |
|----------|------------|----------------|--------|
| WEP      | RC4        | Static keys     | Deprecated |
| WPA      | TKIP       | PSK or 802.1X   | Deprecated |
| WPA2     | AES-CCMP   | PSK or 802.1X   | Standard |
| WPA3     | AES-GCMP   | SAE or 802.1X   | Modern standard |
