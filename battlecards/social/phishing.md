# 🛡️ Battle Card – Incident Response: Phishing

## 🎯 Objective
Contain phishing attempts, protect users, and prevent credential theft or malware infection.

---

## 🚨 1. Detection & Analysis

| Indicators | First Actions |
|------------|---------------|
| - Suspicious email reported by a user<br>- Users clicking suspicious links<br>- Abnormal login attempts | - [ ] Collect original email (headers, attachments)<br>- [ ] Identify targeted users<br>- [ ] Check if credentials were entered or malware executed<br>- [ ] Assess severity |

---

## 🛑 2. Containment
- [ ] Block sender/domain at mail gateway  
- [ ] Remove malicious emails from inboxes  
- [ ] Reset compromised credentials  
- [ ] Enforce/enable MFA  

---

## 🧹 3. Eradication & Recovery
- [ ] Remove malicious attachments and links  
- [ ] Check mailbox rules (forwarding, redirection)  
- [ ] Strengthen spam filters / DNS filtering  

---

## 📋 4. Communication & Escalation
- Notify SOC, IR team, IT security leadership  
- Inform affected users and provide guidance  

---

## 🔄 5. Post-Incident
- [ ] Conduct phishing awareness training  
- [ ] Improve detection and filtering rules  
- [ ] Add IOCs to SIEM/monitoring  

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- Internal IR Playbooks  
