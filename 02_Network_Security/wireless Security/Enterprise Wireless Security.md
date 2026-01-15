# Enterprise Wireless Security

## Authentication Protocols

### EAP (Extensible Authentication Protocol)
- Framework, not a protocol.
- Used to pass authentication info between client and server.

### PEAP (Protected EAP)
- Encapsulates EAP in a TLS tunnel.
- Common with Microsoft environments.

### EAP-TLS
- Uses certificates on both client and server.
- Very secure, but complex to manage.

### EAP-TTLS
- Only server needs a certificate.
- Client uses username/password inside secure tunnel.

## RADIUS (Remote Authentication Dial-In User Service)
- Centralized AAA (Authentication, Authorization, Accounting).
- Encrypts only the password.
- Common in enterprise Wi-Fi setups with 802.1X.

## 802.1X
- Port-based network access control.
- Uses RADIUS for authentication.
- Often paired with EAP methods.

## Key Concept
- Enterprise networks do **not** use pre-shared keys (PSK).
- Instead, use username/password or certificates through an authentication server.
