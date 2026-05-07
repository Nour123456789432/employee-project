# 🧑‍💼 Système de Gestion des Employés

Une application web développée avec **Django** permettant de gérer les employés d'une entreprise via les opérations CRUD complètes.

---

## 🚀 Fonctionnalités

- ➕ Ajouter un employé
- 📋 Afficher la liste des employés
- ✏️ Modifier les informations d'un employé
- ❌ Supprimer un employé avec confirmation

---

## 🛠️ Technologies

| Technologie | Rôle |
|-------------|------|
| Python 3 | Langage principal |
| Django | Framework web backend |
| SQLite | Base de données |
| HTML/CSS | Interface utilisateur |

---

## 📁 Structure du Projet

```
app-django/
│
├── employe/
│   ├── templates/employe/
│   │   ├── base.html
│   │   ├── list.html
│   │   ├── formulaire.html
│   │   └── confirmer_suppression.html
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
│
├── employe_project/
│   ├── settings.py
│   └── urls.py
│
├── .gitignore
├── manage.py
└── README.md
```

---

## ⚙️ Installation

### 1. Cloner le projet
```bash
git clone https://github.com/Nour123456789432/employee-project.git
cd employee-project
```

### 2. Créer un environnement virtuel
```bash
python -m venv .venv
.venv\Scripts\Activate.ps1   # Windows PowerShell
```

### 3. Installer Django
```bash
pip install django
```

### 4. Appliquer les migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Lancer le serveur
```bash
python manage.py runserver
```

### 6. Accéder à l'application
```
http://127.0.0.1:8000/
```

---

## 🧠 Architecture MVT

- **Model** → Structure de la base de données (ORM)
- **View** → Logique métier (ajouter, modifier, supprimer)
- **Template** → Interface utilisateur (HTML)
- **URL** → Connexion entre navigateur et vues

---

## 👨‍💻 Auteur

Projet réalisé par **Nour** dans un objectif d'apprentissage du développement web avec Django.