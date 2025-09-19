# 📝 Battle Card – Unauthorized Use of Resources (Cryptojacking, Shadow IT)

## 🎯 Purpose
Guide to detect and respond to **unauthorized or abusive use of organizational resources**, such as cryptomining, personal projects, or shadow IT.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor resource usage | Detect unusual CPU, GPU, or network spikes. | SOC |
| Review logs | Check for unauthorized apps, containers, or VMs. | IT / IR |
| Identify accounts | Determine if insider or external attacker initiated usage. | IR |
| Assess impact | Estimate business disruption and costs. | Management |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Stop unauthorized processes | Terminate suspicious workloads. | IT |
| Disable compromised accounts | Remove access if insider or external misuse confirmed. | IT |
| Preserve evidence | Save system images and logs. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove unauthorized tools | Delete mining software, shadow IT services. | IT |
| Patch exploited systems | Fix vulnerabilities that allowed deployment. | IT |
| Restore normal services | Return resources to business functions. | IT |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify stakeholders | Brief management on misuse and resource impact. | IR Lead |
| HR/legal review | If insider misuse, involve HR and Legal. | HR / Legal |
| External providers | Notify cloud or hosting providers if resources abused. | IT |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document origin and detection effectiveness. | IR |
| Strengthen controls | Implement quotas, monitoring, and policy enforcement. | Security |
| Awareness & policy | Reinforce acceptable use policies. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- ENISA – *Threat Landscape: Cryptojacking*  
