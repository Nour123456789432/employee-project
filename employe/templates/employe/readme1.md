# 🧑‍💼 Système de Gestion des Employés - Django

---

## 📌 Description du projet

Ce projet est une application web simple développée avec le framework *Django*.
Elle permet de gérer les employés d’une entreprise avec les opérations de base :

- Ajouter un employé
- Afficher la liste des employés
- Modifier un employé
- Supprimer un employé avec confirmation

Ce projet a été réalisé dans un objectif pédagogique pour comprendre le développement web backend avec Django.

---

## ⚙️ Fonctionnalités

- ➕ Création d’un nouvel employé via un formulaire
- 📋 Affichage de tous les employés dans une liste
- ✏️ Modification des informations d’un employé
- ❌ Suppression d’un employé avec confirmation

---

## 🛠️ Technologies utilisées

- Python 3
- Django Framework
- HTML (templates Django)
- CSS basique
- Base de données SQLite

---

## 📁 Structure du projet

app-django/
│
├── employe/
│   ├── templates/employe/
│   │   ├── base.html
│   │   ├── list.html
│   │   ├── formulaire.html
│   │   ├── confirmer_suppression.html
│   │
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│
├── employe_project/
│   ├── settings.py
│   ├── urls.py
│
├── db.sqlite3
├── manage.py

---

## 🧠 Architecture (Django MVT)

- *Model* → structure de la base de données
- *View* → logique métier (ajouter, modifier, supprimer)
- *Template* → interface utilisateur (HTML)
- *URL* → connexion entre navigateur et vues

---

## 🔁 Opérations CRUD

| Opération | Description |
|----------|-------------|
| CREATE | Ajouter un employé |
| READ | Afficher les employés |
| UPDATE | Modifier un employé |
| DELETE | Supprimer un employé |

---

## 🚀 Installation et exécution

### 1. Installer Django
```bash
'pip install django'

 **creer les migrations**

python manage.py makemigrations
python manage.py migrate


---

3. Lancer le serveur

python manage.py runserver


---

4. Accéder à l’application

http://127.0.0.1:8000/


---

📌 Concepts importants appris

Structure d’un projet Django

Système des URLs

Gestion des formulaires

Communication entre HTML et Python

Utilisation de la base de données (ORM)

Opérations CRUD



---

🎯 Objectif du projet

Ce projet permet de comprendre les bases du développement web backend avec Django et de construire une application simple de gestion de données.


---

👨‍💻 Auteur

Projet réalisé par un étudiant dans un objectif d’apprentissage du développement web avec Django.


---

📌 Conclusion

Ce projet est une base fondamentale pour évoluer vers des applications plus avancées comme :

systèmes avec authentification

API REST

dashboards professionnels



---

📝 Type de fichier

Ce document est un fichier README.md écrit en Markdown.
Il est utilisé pour expliquer un projet sur GitHub ou dans un projet de développement.

