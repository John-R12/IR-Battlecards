# 📝 Battle Card – Denial of Service (DoS/DDoS)

## 🎯 Purpose
Concise response guide for **Denial of Service (DoS/DDoS)** attacks.  
Aligned with NIST SP 800-61r2 phases.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Detect abnormal traffic | Monitor spikes in bandwidth, connection attempts, or latency. | SOC |
| Confirm impact | Check service availability and customer reports. | SOC / IT |
| Identify attack type | Volumetric, protocol, or application layer. | SOC |
| Collect evidence | Traffic captures, firewall/IDS logs. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Rate limiting | Apply temporary throttling or filtering rules. | IT / SOC |
| Geo/IP blocking | Block malicious IP ranges where possible. | SOC |
| Engage ISP / CDN | Request upstream filtering, scrubbing services. | IT / Vendor |
| Preserve traffic data | Save NetFlow, logs, and packet captures. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Mitigate at source | Work with ISP/CDN to block traffic upstream. | IT |
| Restore services | Gradually re-enable services once traffic is mitigated. | IT |
| Strengthen defenses | Implement DDoS protection appliances, WAF, rate-limits. | Security |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Internal notification | Inform IT leadership and customer support. | IR Lead |
| External vendors | Coordinate with ISP, CDN, hosting providers. | IT |
| Customer communication | Status page or public announcement if outage is prolonged. | Comms |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document attack vectors and effectiveness of defenses. | IR Lead |
| Update infrastructure | Improve redundancy, add cloud DDoS mitigation. | IT |
| Testing | Perform stress tests and red team simulations. | Security |

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- NIST SP 800-53 SC-5 – Denial of Service Protection  
