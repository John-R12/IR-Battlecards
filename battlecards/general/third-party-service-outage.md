# 📝 Battle Card – Third-Party Service Outage

## 🎯 Purpose
Guide to handle disruptions caused by **unavailability of external providers** (cloud services, SaaS, ISPs, payment systems).

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor availability | Detect failures in third-party APIs or services. | IT / SOC |
| Validate root cause | Confirm issue is external (not internal misconfiguration). | IR |
| Check provider status | Review vendor dashboards and announcements. | IT |
| Assess business impact | Identify processes or customers affected. | Management |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Implement workarounds | Switch to backup providers or manual processes. | IT / Business |
| Prioritize services | Focus resources on most critical functions. | Management |
| Communicate internally | Inform staff of affected systems. | IR Lead |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Wait for vendor resolution | Track status until services restored. | IT |
| Validate restored services | Test functionality before full usage. | IT |
| Synchronize data | Ensure no loss or corruption after downtime. | IT |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify leadership | Provide impact assessment and timeline. | IR Lead |
| Customer updates | Inform clients if services they use are degraded. | Comms / PR |
| Escalate to vendor | Open critical support tickets with provider. | IT / Vendor Mgmt |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Review dependency risks and downtime tolerance. | IR |
| Update vendor risk register | Track outage frequency and SLAs. | Risk Mgmt |
| Strengthen resilience | Add redundancy, multi-provider strategies. | IT / Security |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- NIST SP 800-161 – *Supply Chain Risk Management*  
