# 📡 Gestion des Subscribers - Java  

Ce projet implémente un système de gestion de **subscribers** pour un service d'envoi de messages. 📬  

## 🏗️ Structure du projet  

Le programme permet de gérer une liste d'abonnés (**subscribers**) pouvant recevoir des messages via **quatre modes de communication différents**.  

### 📂 Fichiers principaux  

- **`TestServer.java`** : Contient le `main` et permet de tester le fonctionnement du système.  
- **Autres classes** : Gestion des abonnés et des modes de communication.  

### 📬 Modes de communication disponibles  
1. 📧 **Email**  
2. 📱 **SMS**  
3. 📞 **Xmess**  (réseau social fictif)
4. 💬 **chat**  (moyen de communication alternatif)
Les messages sont juste des system.out.println en console.

## 🎯 Objectif du projet  

- 📜 Implémenter un système modulaire et extensible.  
- 🔄 Utiliser l’**héritage et le polymorphisme** pour la gestion des modes de communication.  
- 🛠️ Faciliter l’ajout de nouveaux types de communication si nécessaire.  
