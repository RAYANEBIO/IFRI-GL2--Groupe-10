# IFRI-GL2 – Projet Odoo

## 📌 Présentation du projet

**Nom du projet :** Digitalisation et centralisation des processus métiers de TechDistrib SARL  
**Odoo Version :** 16.0 (à adapter si nécessaire)  
**Technologies utilisées :** Python, PostgreSQL, Odoo, XML, HTML, CSS  

Ce projet consiste à mettre en place un **ERP Odoo** pour automatiser et centraliser les processus métiers de TechDistrib SARL, une société spécialisée dans la distribution de matériel informatique. Le système gère :  

- Gestion des ventes et devis  
- Gestion des clients et contacts  
- Gestion des stocks et des produits  
- Gestion de la facturation  

---

## 🛠️ Installation

1. Cloner le projet :

```bash
git clone https://github.com/RAYANEBIO/IFRI-GL2--Groupe-10.git
cd IFRI-GL2--Groupe-10

2. Créer un environnement virtuel Python :



python3 -m venv venv
source venv/bin/activate  # sur Linux/macOS
venv\Scripts\activate     # sur Windows

3. Installer les dépendances :



pip install -r requirements.txt

4. Lancer Odoo :
./odoo-bin -c odoo.conf

5. Accéder à l’ERP depuis le navigateur :

http://localhost:8069


---

⚙️ Utilisation

Créer des clients dans le module Ventes

Créer et confirmer des devis

Suivre les commandes et factures

Gérer les produits et le stock



---

📝 Structure du projet

IFRI-GL2-Odoo/
├── addons/        # Modules personnalisés
├── odoo-bin       # Fichier exécutable Odoo
├── odoo.conf      # Configuration du serveur
├── requirements.txt
├── README.md
└── .gitignore


---

💡 Remarques importantes

Ne pas inclure les fichiers de base de données (.db) dans le dépôt.

Fichiers sensibles comme .env sont ignorés dans .gitignore.

Compatible avec Odoo 16.0, PostgreSQL 13+.

---

🔗 Liens utiles

Documentation Odoo

Odoo GitHub
---
👤 Auteur

Rayane Rex – Projet réalisé dans le cadre de l’IFRI GL2 – Groupe 10
