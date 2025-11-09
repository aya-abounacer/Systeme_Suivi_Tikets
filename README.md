# 🎫 Système de Suivi des Tickets IT  
**Application Web de Gestion et de Suivi des Tickets de Support Informatique**

---

## 🌍 Accès

- **Application :** [http://localhost:8080](http://localhost:8080)  
- **Base de données :** `localhost:3306` *(user: root / password: root)*  
- **E-mails :** configurés dans `application.properties` via **JavaMail API**

---

## 🧱 Fonctionnalités Principales

### 👤 Utilisateur
- Création et suivi de tickets  
- Réception de notifications e-mail  
- Consultation de l’historique personnel  

### 🧰 Technicien
- Consultation des tickets assignés  
- Mise à jour du statut (`OPEN`, `IN_PROGRESS`, `RESOLVED`)  
- Ajout de commentaires et notes de résolution  

### 👩‍💼 Administrateur
- Gestion des utilisateurs et des rôles  
- Attribution manuelle des tickets aux techniciens  
- Suivi global et statistiques  

---

## 🧮 Modèle de Données

**Tables principales :**
- `users` → informations et rôles des utilisateurs  
- `tickets` → détails des demandes et statuts  
- `assignments` → lien ticket ↔ technicien  
- `comments` → historique de communication  
- `notifications` → suivi des e-mails envoyés  

✅ La base est conçue pour garantir intégrité référentielle, sécurité et extensibilité.  


---


## 🧭 Perspectives d’Amélioration

- 📊 Tableau de bord d’analyse pour les administrateurs  
- ⏱️ Suivi des délais de traitement (SLA)  
- 🧾 Export PDF / Excel des tickets  
- ⚙️ Migration future vers **Spring Boot REST API + React**

---

## 🎓 Contexte Académique

Projet réalisé dans le cadre du module **Systèmes Répartis et Distribués**  
du **Master d’Excellence en Ingénierie Logicielle** à  
**l’Université Ibn Zohr – Centre d’Excellence IT (Agadir)**.  
