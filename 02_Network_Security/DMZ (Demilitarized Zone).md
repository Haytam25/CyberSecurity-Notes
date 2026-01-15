## 🔍 Definition
A DMZ is a physical or logical subnetwork that contains and exposes external-facing services to an untrusted network, usually the internet.

## 🏗️ Architecture
[Internet] ⇄ [Firewall] ⇄ [DMZ] ⇄ [Internal Network]
![[Pasted image 20250704200405.png]]
## 💡 Purpose
- Isolate public services from the internal LAN
- Limit access if a public-facing service is compromised

## 📦 Services in a DMZ
- Web servers
- Email servers
- DNS servers

## 🔐 Security Tips
- Use firewalls between all zones
- Do not allow DMZ hosts to initiate connections to internal network