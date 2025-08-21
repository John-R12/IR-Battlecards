# 📝 Battle Card – Lost or Stolen Device

## 🎯 Purpose
Concise response guide for **Lost or Stolen Device** incidents (laptop, smartphone, USB).  
Aligned with NIST SP 800-61r2 phases.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Report incident | User reports loss/theft of device. | Employee / IT |
| Assess device type | Determine if device is laptop, mobile, removable media. | IT |
| Identify data at risk | Check if device contained sensitive data or access tokens. | IR |
| Confirm protections | Was disk encrypted, remote wipe enabled, MFA required? | IT |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Revoke access | Disable VPN, AD, email, and app sessions linked to device. | IT |
| Remote wipe | Trigger remote wipe if capability exists. | IT |
| Block device | Add IMEI/serial number to MDM blocklist if possible. | IT |
| Preserve evidence | Document loss, location (if GPS), and last known activity. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Replace hardware | Issue replacement device to user. | IT |
| Restore data | Provide user with clean system and required files. | IT |
| Apply stronger controls | Enforce encryption, MDM, EDR, stronger password policies. | Security |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Internal notification | Notify IT, Security, and management. | IR Lead |
| External reporting | If sensitive data, escalate to Legal for breach disclosure assessment. | Legal |
| Law enforcement | File a report if device theft is suspected. | Legal / Management |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Analyze root cause (negligence, theft, missing controls). | IR |
| Update policy | Revise mobile device and data handling policies. | Security / HR |
| Awareness | Educate users on secure handling of mobile devices. | HR / Security |

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- NIST SP 800-124 – *Guidelines for Managing the Security of Mobile Devices*  
