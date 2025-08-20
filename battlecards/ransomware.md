# 🛡️ Battle Card – Réponse à Incident : Ransomware

## 🎯 Objectif
Limiter la propagation, éradiquer le ransomware et restaurer l’activité en minimisant l’impact.

---

## 🚨 1. Détection & Analyse

| Signes d’alerte | Premières actions |
|-----------------|-------------------|
| - Messages de rançon<br>- Fichiers chiffrés (.locked, .encrypted, etc.)<br>- Activité réseau anormale (pics SMB/RDP)<br>- Alertes EDR / antivirus | - [ ] Noter la date/heure de détection<br>- [ ] Identifier les systèmes impactés<br>- [ ] Sauvegarder les preuves (logs, copies mémoire, échantillons)<br>- [ ] Classer la sévérité (souvent **critique**) |

---

## 🛑 2. Containment (Confinement)
- [ ] Isoler immédiatement la machine compromise (sans l’éteindre)  
- [ ] Désactiver les comptes compromis  
- [ ] Segmenter/déconnecter les parties critiques du réseau  
- [ ] Bloquer IOC connus (IPs, hash, domaines) sur firewall/EDR  

---

## 🧹 3. Eradication & Recovery
- [ ] Identifier la souche du ransomware  
- [ ] Supprimer le binaire et les mécanismes de persistance  
- [ ] Scanner tout l’environnement  
- [ ] Restaurer depuis des sauvegardes **non infectées**  
- [ ] Appliquer correctifs et changer les identifiants compromis  

---

## 📋 4. Communication & Escalade
- Prévenir : SOC / CERT interne, CISO, DSI, Juridique, Autorités (ANSSI, Police)  
- ⚠️ **Ne jamais communiquer avec les attaquants sans validation direction/juridique.**

---

## 🔄 5. Post-Incident
- [ ] Rédiger un rapport complet  
- [ ] Débrief (REX) avec parties prenantes  
- [ ] Mettre à jour procédures et sauvegardes  
- [ ] Sensibiliser les utilisateurs  

---

## 📚 Références utiles
- NIST SP 800-61r2  
- ANSSI – Guide ransomware  
- Playbook interne SOC n°RANS-01  
