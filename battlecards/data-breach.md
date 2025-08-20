# 🛡️ Battle Card – Réponse à Incident : Data Breach (Fuite de données)

## 🎯 Objectif
Limiter l’exposition de données sensibles et répondre aux obligations légales.

---

## 🚨 1. Détection & Analyse

| Signes d’alerte | Premières actions |
|-----------------|-------------------|
| - Exfiltration suspecte dans logs<br>- Fichiers sensibles retrouvés sur internet<br>- Notification d’un tiers (CERT, client, partenaire) | - [ ] Identifier les données concernées<br>- [ ] Déterminer l’ampleur (utilisateurs impactés, systèmes compromis)<br>- [ ] Sauvegarder preuves (logs, forensic)<br>- [ ] Classer la sévérité |

---

## 🛑 2. Containment (Confinement)
- [ ] Isoler le système compromis  
- [ ] Couper la fuite en cours (bloquer exfiltration)  
- [ ] Désactiver comptes compromis  
- [ ] Révoquer accès API/partenaires si nécessaires  

---

## 🧹 3. Eradication & Recovery
- [ ] Supprimer backdoors, malwares, comptes suspects  
- [ ] Patcher vulnérabilités exploitées  
- [ ] Restaurer configuration sécurisée  

---

## 📋 4. Communication & Escalade
- [ ] Informer : SOC, CISO, Juridique, Direction générale  
- [ ] Déclarer l’incident à la CNIL (72h) si données personnelles impactées  
- [ ] Informer clients/partenaires concernés  

---

## 🔄 5. Post-Incident
- [ ] Rédiger rapport d’incident et chronologie  
- [ ] Analyser causes profondes  
- [ ] Mettre en place mesures de protection renforcées  

---

## 📚 Références utiles
- NIST SP 800-61r2  
- CNIL – Notification de violation de données  
- ANSSI – Gestion des incidents  
