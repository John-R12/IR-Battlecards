# 📝 Battle Card – Web Application Attack

## 🎯 Purpose
Guide for responding to **web application attacks** (SQL Injection, XSS, RCE, directory traversal, etc.).

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Review WAF alerts | Investigate suspicious requests and exploit attempts. | SOC |
| Check logs | Analyze web server, app logs, and error messages. | SOC / DevOps |
| Validate vulnerability | Confirm presence of exploited weakness. | IR |
| Identify impact | Check data exposure or service degradation. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Block malicious IPs | Implement WAF or firewall blocks. | SOC |
| Disable vulnerable endpoints | Temporarily take vulnerable features offline. | DevOps |
| Preserve artifacts | Save HTTP logs, exploit payloads, web responses. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Patch vulnerability | Apply fixes, update frameworks, or reconfigure server. | DevOps |
| Validate remediation | Retest using security tools and penetration testing. | Security |
| Harden environment | Enable stricter input validation, WAF rules, CSP. | Security |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify teams | Inform DevOps, security, and app owners. | IR Lead |
| Vendor coordination | If vulnerability is in a 3rd-party library. | DevOps |
| Legal review | If data breach suspected. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document attack vector and root cause. | IR |
| Code review | Implement secure coding practices. | DevOps |
| Continuous testing | Regularly run vulnerability scans and pentests. | Security |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- OWASP Top 10  
