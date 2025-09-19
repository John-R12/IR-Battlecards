# 📋 Checklist – Host Isolation

Use this checklist when isolating a potentially compromised endpoint or server.  
Goal: **stop attacker activity while preserving evidence.**

---

## ✅ Before Isolation
- [ ] Verify suspicious activity (alerts, logs, user reports).  
- [ ] Inform SOC/IR lead of planned isolation.  
- [ ] Identify business criticality of the host.  
- [ ] Prepare containment method (EDR, firewall, network switch).  

---

## 🚨 During Isolation
- [ ] Isolate via EDR or network ACL (do not power off).  
- [ ] Preserve volatile data (memory dump, active connections).  
- [ ] Record host details (hostname, IP, user, asset owner).  
- [ ] Communicate isolation to relevant IT/business owner.  

---

## 🧹 After Isolation
- [ ] Tag system as "quarantined" in asset inventory.  
- [ ] Ensure monitoring continues (logs, sensors).  
- [ ] Escalate to forensic analysis if required.  
- [ ] Document actions, timestamps, and responsible person.  

---

✅ **Reminder:** Avoid shutting down the system unless absolutely necessary — memory and evidence may be lost.  
