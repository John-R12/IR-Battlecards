# 📝 Battle Card – Critical Infrastructure Attack (ICS/SCADA)

## 🎯 Purpose
Guide to respond to attacks on **Industrial Control Systems (ICS)** or **SCADA environments**.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor OT/ICS systems | Detect abnormal control commands or process deviations. | SOC / OT Security |
| Review network segmentation | Check for IT-to-OT lateral movement. | IR |
| Identify affected processes | Determine operational impact on critical services. | OT Teams |
| Correlate with threat intel | Match activity with known ICS attack patterns. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Isolate affected ICS systems | Disconnect compromised controllers if safe. | OT Security |
| Segregate networks | Block IT/OT connections if intrusion detected. | Network / OT Security |
| Preserve evidence | Collect logs, PLC configs, and network captures. | IR / OT Teams |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove malware/backdoors | Clean infected devices and HMIs. | OT Security |
| Restore control logic | Re-upload validated PLC configurations. | OT Teams |
| Validate operations | Ensure industrial processes run safely. | OT / Engineering |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify leadership | Escalate to critical infrastructure operators. | IR Lead |
| Regulatory reporting | Notify national regulators if required. | Legal / Compliance |
| Coordinate with CERT/ISAC | Share anonymized findings with trusted partners. | IR |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document ICS-specific vulnerabilities and gaps. | IR / OT Teams |
| Strengthen defenses | Improve segmentation, monitoring, and OT security. | Security / OT |
| Training & awareness | Train engineers and operators on cyber threats. | OT Security |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- NIST SP 800-82 – *Guide to ICS Security*  
