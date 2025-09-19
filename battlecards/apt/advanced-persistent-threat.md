# 📝 Battle Card – Advanced Persistent Threat (APT)

## 🎯 Purpose
Guide to detect and respond to **sophisticated, long-term intrusions** by advanced adversaries.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor anomalies | Look for unusual persistence, lateral movement, and beaconing. | SOC |
| Threat intelligence correlation | Match observed TTPs with known APT groups. | IR / Threat Intel |
| Identify foothold | Determine entry point (phishing, zero-day, supply chain). | IR |
| Scope the intrusion | Map affected systems, data, and users. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Isolate compromised assets | Remove from network while maintaining evidence. | IT / IR |
| Block C2 traffic | Identify and block command-and-control channels. | SOC |
| Preserve forensics | Capture memory, disk, and network logs. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove persistence mechanisms | Identify and clean scheduled tasks, backdoors, and implants. | IR |
| Patch exploited vulnerabilities | Close initial access vectors. | IT |
| System restoration | Rebuild or restore affected systems. | IT |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify leadership | Provide executive-level updates. | IR Lead |
| External support | Engage national CERTs, trusted partners, or MSSPs. | IR / Management |
| Legal & regulatory | Evaluate notification obligations if data impacted. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document APT tactics and detection gaps. | IR |
| Threat hunting | Expand detection across environment. | SOC / IR |
| Improve defenses | Enhance EDR, threat intelligence, and monitoring. | Security |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- MITRE ATT&CK – APT Techniques  
