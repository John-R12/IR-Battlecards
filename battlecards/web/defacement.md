# 📝 Battle Card – Website Defacement

## 🎯 Purpose
Guide to detect and respond to **unauthorized modifications of a website’s appearance or content**.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor web changes | Detect unexpected content or visual changes. | SOC / Web Admin |
| User reports | Collect reports from visitors noticing defacement. | Helpdesk |
| Review logs | Check web server, CMS, and application logs. | IR |
| Identify entry vector | Determine if vulnerability, weak credentials, or misconfiguration was exploited. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Take site offline | Temporarily redirect or disable affected web pages. | Web Admin |
| Block attacker access | Change credentials, block malicious IPs. | IT / SOC |
| Preserve evidence | Save compromised pages, logs, and indicators. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Restore clean content | Revert to last known good backup. | Web Admin |
| Patch vulnerabilities | Fix exploited flaws (CMS, plugins, server). | IT / Security |
| Harden system | Apply security headers, WAF rules, MFA for admins. | Security |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify stakeholders | Communicate incident to management and web owners. | IR Lead |
| Public communication | If visible to users, issue official statement. | Comms / PR |
| External partners | Inform hosting provider or CDN if relevant. | IT |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document root cause and detection delays. | IR |
| Improve monitoring | Deploy integrity monitoring tools (file hashes, SIEM rules). | SOC |
| Awareness | Train web admins on secure practices. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- OWASP – *Web Security Testing Guide*  
