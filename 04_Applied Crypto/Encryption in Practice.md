## Common Use Cases

### 1. Web Security
- HTTPS encrypts traffic between browser and server using TLS.
- Websites use digital certificates for identity validation.

### 2. Email Encryption
- **S/MIME**: Built into many email clients; uses X.509 certificates.
- **PGP**: User-managed key pairs for encrypting emails.

### 3. Disk Encryption
- **BitLocker** (Windows) / **FileVault** (macOS)
- Protects data at rest using full disk encryption.

### 4. VPN Authentication
- VPNs often use certificates for identity verification (SSL VPNs).

### 5. Secure File Transfer
- **SFTP** uses SSH for secure file transfer.
- TLS can also be used in FTPS.

## Good Practices
- Use strong keys (2048-bit RSA or better).
- Always validate certificates.
- Revoke compromised or expired certificates promptly.