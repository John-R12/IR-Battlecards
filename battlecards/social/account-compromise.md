# 🛡️ Battle Card – Incident Response: Account Compromise

## 🎯 Objective
Prevent attackers from leveraging compromised credentials to access sensitive systems.

---

## 🚨 1. Detection & Analysis

| Indicators | First Actions |
|------------|---------------|
| - Suspicious logins (impossible travel, abnormal geolocation)<br>- High failed login rates<br>- SIEM/EDR alerts | - [ ] Identify the compromised account<br>- [ ] Record time and scope of compromise<br>- [ ] Investigate malicious activity performed with the account |

---

## 🛑 2. Containment
- [ ] Suspend compromised account  
- [ ] Reset password and enforce MFA  
- [ ] Invalidate active sessions  

---

## 🧹 3. Eradication & Recovery
- [ ] Remove malicious mailbox rules or delegations  
- [ ] Review recent account activity  
- [ ] Reinstate account only after secure validation  

---

## 📋 4. Communication & Escalation
- Notify SOC, IR team, CISO, and IT management  
- Inform affected user(s)  

---

## 🔄 5. Post-Incident
- [ ] Add IOCs to SIEM and monitoring rules  
- [ ] Strengthen authentication policies (MFA, conditional access)  
- [ ] Provide security awareness for the affected user(s)  

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- Internal IR Playbooks  
