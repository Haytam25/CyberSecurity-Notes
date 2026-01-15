## 🔍 IDS (Intrusion Detection System)
Monitors network traffic for suspicious activity and sends alerts.

## 🔐 IPS (Intrusion Prevention System)
Monitors and actively blocks malicious traffic.
- It could be a Fail Open { when the system fails data flow }or Fail Closed System { when the system fails data does not flow}
## Device Connection (IPS)
### Active Monitoring 
![[Pasted image 20250704201948.png]]
### Passive Monitoring
![[Pasted image 20250704202009.png]]
 **==In this case the IPS will function as a IDS because the IPS does not have a way to intercept the traffic==** 
## ⚙️ Types of Detection
- **Signature-Based**: Matches known attack patterns
- **Anomaly-Based**: Detects deviations from normal behavior

## 🏗️ Placement
- IDS: Out-of-band (passive)
- IPS: Inline (active)

## ⚠️ Challenges
- False positives/negatives
- Performance overhead