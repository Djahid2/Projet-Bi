# Projet ETL & Business Intelligence – Northwind

## 1. Contexte et Objectifs
Ce projet a pour objectif la conception et la mise en œuvre d’un processus **ETL (Extract, Transform, Load)** appliqué à la base de données **Northwind**, en utilisant deux approches différentes : **Talend** et **Power BI**.

L’objectif principal est :
- D’extraire les données depuis **Northwind SQL Server** et **Northwind Access**,
- De transformer et structurer les données selon une logique **Data Warehouse**,
- De comparer les capacités, performances et limites de **Talend** et **Power BI** dans un contexte ETL,
- De réaliser des **analyses de Business Intelligence** à partir des données intégrées.

Ce projet s’inscrit dans une démarche analytique et académique, orientée **décisionnel** et **aide à la prise de décision**.

---

## 2. Périmètre du Projet
- Sources de données :
  - Base **Northwind SQL Server**
  - Base **Northwind Microsoft Access**
- Outils ETL :
  - **Talend Open Studio**
  - **Power BI (Power Query)**
- Restitution :
  - Modélisation **Data Warehouse**
  - Tableaux de bord Power BI
  - Analyses décisionnelles (KPI, indicateurs de performance)

---

## 3. Architecture Générale
Le projet suit l’architecture décisionnelle classique :

1. **Sources de données** (SQL Server / Access)
2. **ETL** (Talend / Power BI)
3. **Zone de stockage / Data Warehouse**
4. **Analyse BI et Visualisation**

---

## 4. Structure du Projet

```text
project-root/
│
├── data/
│   
│
├── power bi/
│
├── python/ 
│
├── Rapport/
│   
├── sql/
│   
├── Talend/
│   
│
├── video/
│  
└── README.md               # Documentation générale du projet
```

---

## 5. Processus ETL

### 5.1 Extraction
- Connexion aux bases **Northwind SQL Server** et **Northwind Access**
- Extraction des tables principales : Orders, Order Details, Customers, Products, Employees, Suppliers

### 5.2 Transformation
- Nettoyage des données (valeurs nulles, doublons)
- Harmonisation des formats (dates, clés, types)
- Création de dimensions et de faits
- Calcul des indicateurs métier (commandes livrées, non livrées, chiffre d’affaires)

### 5.3 Chargement
- Chargement dans une structure **Data Warehouse**
- Modélisation en étoile (Star Schema)

---

## 6. Comparaison Talend vs Power BI

| Critère | Talend | Power BI |
|-------|--------|----------|
| Orientation | ETL industriel | ETL + Visualisation |
| Complexité | Élevée | Moyenne |
| Automatisation | Avancée | Limitée |
| Scalabilité | Forte | Moyenne |
| Visualisation | Faible | Excellente |

Cette comparaison permet d’identifier les cas d’usage optimaux pour chaque outil.

---

## 7. Analyse Business Intelligence

Les analyses BI portent sur :
- Performance des commandes par client
- Taux de livraison vs non-livraison
- Analyse des ventes par pays et par produit
- Identification des clients stratégiques
- Risques de concentration et dépendance client

Ces analyses visent à fournir des **insights décisionnels exploitables**.

---

## 8. Résultats et Apports
- Mise en place d’un ETL complet et reproductible
- Comparaison objective de deux outils BI majeurs
- Valorisation des données Northwind via des indicateurs métier
- Support à la prise de décision stratégique

---

## 9. Technologies Utilisées
- SQL Server
- Microsoft Access
- Talend Open Studio
- Power BI
- SQL

---

## 10. Auteur
Projet réalisé dans un cadre académique à des fins d’apprentissage et d’analyse décisionnelle.

