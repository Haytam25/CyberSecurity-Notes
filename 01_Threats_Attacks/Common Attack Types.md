## 🌀 Denial of Service (DoS) / Distributed Denial of Service (DDoS)

### Definition
> An attack that aims to overwhelm a system or network, making it unavailable to users.

### Types:
- **DoS**: Single source attacks.
- **DDoS**: Multiple sources (botnets) flooding the target.

### Techniques:
- SYN Floods
- UDP Floods
- Application-layer (Layer 7) attacks

### Defense:
- Firewalls & IDS/IPS
- Rate limiting
- Blackhole routing
- Anti-DDoS services (Cloudflare, AWS Shield)

---

## 🕵️ Insider Threats

### Definition
> Threats posed by individuals within the organization (e.g., employees, contractors).

### Types:
- **Malicious insiders**: Intentional harm or theft.
- **Negligent insiders**: Unintended harm (e.g., weak password sharing).
- **Compromised insiders**: Credential theft (e.g., phishing victim).

### Mitigation:
- User behavior analytics
- Access controls (least privilege)
- Training and awareness
- DLP (Data Loss Prevention) systems

---

## 🔑 Brute Force Attacks

### Definition
> Repeated attempts to guess login credentials using automation.

### Types:
- **Simple brute force**: Tries all possible combinations.
- **Dictionary attack**: Tries words from a list.
- **Credential stuffing**: Uses known credentials from past breaches.

### Defense:
- Lockouts / account throttling
- CAPTCHA
- Strong passwords
- MFA (Multi-Factor Authentication)

---

## 📎 Related Notes
- [Social Engineering](01_Threats_and_Attacks/Social_Engineering.md)
- [Malware Types](01_Threats_and_Attacks/Malware.md)