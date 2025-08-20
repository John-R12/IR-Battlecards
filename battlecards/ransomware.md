# 🛡️ Battle Card – Incident Response: Ransomware

## 🎯 Objective
Limit the spread, eradicate the ransomware, and restore business operations while minimizing impact.

---

## 🚨 1. Detection & Analysis

| Indicators | First Actions |
|------------|---------------|
| - Ransom note displayed<br>- Encrypted files (.locked, .encrypted, etc.)<br>- Unusual network activity (SMB/RDP spikes)<br>- Alerts from EDR/antivirus | - [ ] Record detection time<br>- [ ] Identify affected systems<br>- [ ] Preserve evidence (logs, memory dumps, samples)<br>- [ ] Assess severity (usually **critical**) |

---

## 🛑 2. Containment
- [ ] Isolate infected hosts (do not power off)  
- [ ] Disable compromised accounts  
- [ ] Disconnect or segment critical network segments  
- [ ] Block known IOCs (IPs, hashes, domains) on firewalls/EDR  

---

## 🧹 3. Eradication & Recovery
- [ ] Identify ransomware family (via hash, ransom note)  
- [ ] Remove binaries and persistence mechanisms  
- [ ] Scan the environment for additional infections  
- [ ] Restore systems from **clean backups**  
- [ ] Apply patches and reset compromised credentials  

---

## 📋 4. Communication & Escalation
- Notify: SOC, Incident Response team, CISO, IT management, Legal/Compliance  
- ⚠️ **Do not engage with attackers unless approved by management and legal.**

---

## 🔄 5. Post-Incident
- [ ] Draft full incident report and timeline  
- [ ] Conduct lessons learned meeting  
- [ ] Update procedures and backup strategy  
- [ ] Conduct user awareness training  

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- Internal IR Playbooks  
