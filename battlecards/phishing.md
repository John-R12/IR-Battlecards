# 🛡️ Battle Card – Réponse à Incident : Phishing

## 🎯 Objectif
Limiter l’impact d’une campagne de phishing et protéger les utilisateurs.

---

## 🚨 1. Détection & Analyse

| Signes d’alerte | Premières actions |
|-----------------|-------------------|
| - Mail suspect signalé par un utilisateur<br>- Liens suspects cliqués<br>- Connexions anormales à la messagerie | - [ ] Recueillir l’email original (headers, pièce jointe)<br>- [ ] Identifier utilisateurs ciblés<br>- [ ] Vérifier si clics/credentials volés<br>- [ ] Classer la sévérité |

---

## 🛑 2. Containment (Confinement)
- [ ] Bloquer l’expéditeur / domaine au niveau du serveur mail  
- [ ] Supprimer les messages des boîtes de réception  
- [ ] Réinitialiser les mots de passe compromis  
- [ ] Activer MFA si non déployé  

---

## 🧹 3. Eradication & Recovery
- [ ] Nettoyer boîtes impactées (supprimer pièces jointes malveillantes)  
- [ ] Vérifier absence de persistance (règles de boîte aux lettres, redirections)  
- [ ] Renforcer filtrage anti-spam / DNS filtering  

---

## 📋 4. Communication & Escalade
- [ ] Prévenir SOC / CERT interne  
- [ ] Informer DSI et RSSI  
- [ ] Communication interne aux utilisateurs ciblés (alerte vigilance)  

---

## 🔄 5. Post-Incident
- [ ] Sensibiliser utilisateurs (exercice phishing)  
- [ ] Améliorer règles de filtrage et détection  
- [ ] Documenter IOC pour SIEM  

---

## 📚 Références utiles
- NIST SP 800-61r2  
- ANSSI – Guide bonnes pratiques mail  
