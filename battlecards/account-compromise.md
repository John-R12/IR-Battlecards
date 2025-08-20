# 🛡️ Battle Card – Réponse à Incident : Compte Compromis

## 🎯 Objectif
Empêcher l’attaquant d’utiliser un compte compromis pour accéder au SI.

---

## 🚨 1. Détection & Analyse

| Signes d’alerte | Premières actions |
|-----------------|-------------------|
| - Connexions suspectes (géolocalisation anormale, impossible travel)<br>- Alertes SIEM (Azure AD, O365, AD local)<br>- Chiffre d’échec authentification élevé | - [ ] Identifier le compte compromis<br>- [ ] Noter date/heure et périmètre<br>- [ ] Vérifier si actions malveillantes (envoi mails, accès fichiers) |

---

## 🛑 2. Containment (Confinement)
- [ ] Suspendre immédiatement le compte compromis  
- [ ] Réinitialiser mot de passe fort + MFA  
- [ ] Invalider sessions actives  

---

## 🧹 3. Eradication & Recovery
- [ ] Supprimer règles de redirection dans messagerie  
- [ ] Vérifier absence de délégations suspectes  
- [ ] Analyser activités passées du compte  
- [ ] Réactiver uniquement une fois sain et renforcé  

---

## 📋 4. Communication & Escalade
- [ ] Prévenir SOC, CISO, DSI  
- [ ] Alerter utilisateur concerné  
- [ ] Communication interne si campagne large  

---

## 🔄 5. Post-Incident
- [ ] Ajouter IOC liés au compte dans SIEM  
- [ ] Renforcer règles MFA et alerting  
- [ ] Sensibiliser utilisateur impacté  

---

## 📚 Références utiles
- NIST SP 800-61r2  
- Microsoft – Guide réponse compromission O365  
- ANSSI – Authentification forte  
