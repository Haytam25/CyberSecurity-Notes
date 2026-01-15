### 🔐 Purpose

Secure protocols are designed to **protect data in transit** through **encryption**, **authentication**, and **integrity validation**.

---

## 🔑 Common Secure Protocols

|Protocol|Port|Purpose|Notes|
|---|---|---|---|
|**HTTPS**|443|Secure HTTP|Uses TLS to encrypt web traffic|
|**SSH**|22|Secure remote login|Encrypts commands and sessions|
|**SFTP**|22|Secure File Transfer over SSH|Not the same as FTPS|
|**FTPS**|990|FTP with SSL/TLS|Encryption added to traditional FTP|
|**DNSSEC**|—|Secures DNS|Validates responses with digital signatures|
|**SNMPv3**|161|Network management|Adds encryption & authentication to SNMP|
|**IPsec**|500 (IKE)|Secure network layer|Used in VPNs, supports AH & ESP|
|**TLS/SSL**|Varies|Encryption for various protocols|TLS replaces SSL (deprecated)|

---

## 📧 Secure Email Protocols

|Protocol|Port|Function|
|---|---|---|
|**SMTPS**|465|Secure SMTP (sending)|
|**POP3S**|995|Secure POP3 (retrieving)|
|**IMAPS**|993|Secure IMAP (retrieving)|

> 💡 Use TLS-based versions of email protocols to protect credentials and message content.

---

## 🔐 VPN Protocols

### **IPsec**

- Provides: **Authentication**, **Encryption**, **Integrity**
    
- Two modes:
    
    - **Tunnel mode** (entire packet encrypted)
        
    - **Transport mode** (only payload encrypted)
        
- Uses: **IKE**, **AH**, **ESP**
    

### **SSL/TLS VPN**

- Operates at higher layers (Application)
    
- Often used in **clientless VPNs**
    

### **OpenVPN**

- Open-source and flexible
    
- Uses SSL/TLS for key exchange
    

---

## 🚫 Insecure Protocols (Avoid)

|Protocol|Issue|
|---|---|
|**Telnet**|Unencrypted terminal access|
|**FTP**|Unencrypted file transfer|
|**HTTP**|No encryption|
|**SNMP v1/v2**|No encryption or secure auth|
|**POP3 / IMAP / SMTP**|Plain-text credentials|

> 🛑 Replace with encrypted alternatives like SSH, SFTP, HTTPS, SNMPv3.

---

## 🔁 Protocol Comparison Table

| Feature            | SSH | HTTPS | IPsec | TLS   | SFTP |
| ------------------ | --- | ----- | ----- | ----- | ---- |
| **Encryption**     | ✅   | ✅     | ✅     | ✅     | ✅    |
| **Authentication** | ✅   | ✅     | ✅     | ✅     | ✅    |
| **Integrity**      | ✅   | ✅     | ✅     | ✅     | ✅    |
| **Layer**          | App | App   | Net   | Trans | App  |