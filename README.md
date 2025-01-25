# Optimization-of-e-Commerce-Data-Management-with-ETL-SCD-Power-BI
Optimization of e-Commerce Data Management with ETL, SCD, Power BI

# Optimisation de la Gestion des Données e-Commerce avec ETL, SCD et Power BI

## 📚 Description du Projet

Ce projet vise à structurer et analyser efficacement les données d'une plateforme e-commerce en utilisant **Talend** pour les processus ETL, **SQL Server** pour l'entreposage des données, et **Power BI** pour l'analyse visuelle. La gestion des Slowly Changing Dimensions (SCD) est intégrée pour suivre l'évolution des informations critiques. L'objectif principal est d'améliorer la prise de décision, de surveiller les performances des fournisseurs et de mieux comprendre les tendances du marché.

---

## 🛠️ Technologies Utilisées

- **Talend** : Extraction, Transformation, et Chargement (ETL)
- **SQL Server** : Entrepôt de données structuré en schéma constellation
- **Power BI** : Visualisation et analyse des données
- **JSON/CSV** : Formats de données pour les sources initiales

---

## 🚀 Fonctionnalités Principales

1. **Extraction, Transformation et Chargement (ETL) avec Talend :**
   - Nettoyage des données et gestion des valeurs manquantes.
   - Gestion des Slowly Changing Dimensions (SCD) :
     - **Type 1 (Overwrite)** : Mise à jour des données actuelles.
     - **Type 2 (Versioning)** : Suivi des changements historiques.
     - **Type 3 (Tracking a Few Changes)** : Suivi d'un nombre limité de modifications.
   - Chargement des données transformées dans SQL Server.

2. **Modélisation des Données :**
   - Schéma constellation avec des tables de faits et de dimensions :
     - Tables de dimensions : `DateDimension`, `ProductDimension`, `CustomerDimension`, etc.
     - Tables de faits : `SalesFact` et `InventoryFact`.

3. **Analyse et Visualisation avec Power BI :**
   - Analyse des tendances des ventes.
   - Suivi des niveaux d'inventaire.
   - Segmentation des clients et évaluation de la performance des fournisseurs.

4. **Conformité RGPD :**
   - Sécurisation des données sensibles.
   - Mise en place de pratiques de conformité.

5. **Optimisation des Performances :**
   - Indexation et partitionnement pour améliorer les requêtes.
   - Justifications des optimisations implémentées.

---

## 📑 Architecture du Système

Le système repose sur trois étapes principales :  
1. **ETL avec Talend** : Extraction des données des fichiers JSON/CSV, nettoyage et transformation, puis chargement dans l’entrepôt de données.  
2. **Entreposage des Données dans SQL Server** : Schéma constellation permettant une navigation efficace entre les tables de faits et dimensions.  
3. **Visualisation dans Power BI** : Création de tableaux de bord pour une prise de décision éclairée.

---

## 📊 Résultats Attendues

### Data Mart des Ventes :
- Analyse des produits les plus performants.
- Impact des réductions sur les ventes.
- Performance des transporteurs.

### Data Mart de l’Inventaire :
- Niveaux de stock et prévisions de la demande.
- Disponibilité des stocks.
- Suivi des performances des fournisseurs.

---

## 🔐 Sécurité et Gestion des Autorisations

- Mise en place de rôles utilisateurs pour SQL Server.
- Attribution de permissions spécifiques pour chaque utilisateur.
- Respect des exigences RGPD pour la protection des données sensibles.

---

## 📁 Structure du Projet

├── ETL_Scripts/ # Scripts Talend pour ETL 
├── SQL_Schema/ # Scripts de création des tables SQL 
├── PowerBI_Dashboards/ # Fichiers de visualisation Power BI 
├── Data/ # Données sources (JSON/CSV) 
├── Documentation/ # Rapport détaillé et guides 
└── README.md # Documentation du projet



---

## 📄 Documentation

Consultez le [rapport complet](./Documentation/Rapport_Optimisation_Donnees_eCommerce.docx) pour plus de détails sur l’architecture et les implémentations.

---

## 🤝 Contribution

1. Clonez le dépôt :
   ```bash
   git clone git@github.com:AbdeljalilEzzirani/Optimization-of-e-Commerce-Data-Management-with-ETL-SCD-Power-BI.git


## 📬 Contact
Pour toute question, suggestion ou collaboration, n'hésitez pas à me contacter à 
abdeljalilezzirani@gmail.com
.
