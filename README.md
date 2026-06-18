# 🏠 Analyse du marché immobilier français avec SQL

## 🎯 Objectif

Concevoir et exploiter une base de données relationnelle permettant d'analyser les transactions immobilières en France et de produire des indicateurs utiles à la prise de décision.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'objectif est d'intégrer plusieurs sources de données immobilières françaises (DVF, INSEE et données géographiques), de construire une base de données normalisée puis de répondre à différentes problématiques métier à l'aide de requêtes SQL.

## ❓ Problématique

Comment structurer efficacement des données immobilières et exploiter SQL afin d'analyser les prix, les transactions et les dynamiques du marché immobilier français ?

## 📂 Sources de données

* DVF (Demande de Valeurs Foncières)
* Données INSEE
* Données géographiques (communes, départements, régions)

## 🛠️ Méthodologie

### Modélisation de la base

* Création du dictionnaire des données
* Conception du schéma relationnel
* Respect des règles de normalisation (3NF)
* Mise en place des clés primaires et étrangères

### Création de la base

Création des tables :

* Région
* Commune
* Bien
* Vente

### Contrôle qualité

* Vérification de l'intégrité référentielle
* Validation des relations entre tables
* Vérification de la conformité RGPD

## 🗄️ Schéma relationnel

La base repose sur quatre entités principales :

### Région

* Identifiant région
* Nom de la région

### Commune

* Code commune
* Département
* Région
* Population

### Bien

* Adresse
* Type de bien
* Surface
* Nombre de pièces

### Vente

* Date de transaction
* Valeur foncière
* Bien concerné

## 📊 Analyses réalisées

### Activité immobilière

* Nombre total de ventes
* Évolution trimestrielle des transactions
* Analyse régionale des ventes

### Analyse des prix

* Prix moyen au m²
* Régions les plus chères
* Départements les plus chers
* Comparaison appartements / maisons

### Analyse territoriale

* Classement des communes
* Analyse des ventes rapportées à la population
* Comparaison entre régions

### Analyses avancées

* Top des biens les plus chers
* Classement des communes par valeur foncière
* Analyse des prix selon le nombre de pièces
* Utilisation des fonctions analytiques SQL (RANK)

## 🧰 Technologies utilisées

* SQL
* MySQL
* SQLite
* DB Browser
* Excel

## 📁 Structure du projet

```text
sql/
│
├── creation_tables.sql
├── insertion_donnees.sql
├── requetes_analyse.sql

schema/
│
├── schema_relationnel.png

docs/
│
├── dictionnaire_donnees.xlsx
├── presentation.pdf

README.md
```

## 📈 Compétences développées

* SQL avancé
* Jointures complexes
* Agrégations et indicateurs
* Fonctions analytiques (RANK)
* Modélisation relationnelle
* Normalisation 3NF
* Intégrité référentielle
* Analyse immobilière
* Traduction d'un besoin métier en requêtes SQL

## 🔍 Résultats clés

L'analyse permet d'identifier :

* Les régions les plus dynamiques du marché immobilier
* Les zones où le prix au m² est le plus élevé
* Les communes présentant la plus forte pression immobilière
* Les différences de valorisation selon le type de bien et le nombre de pièces

## 👨‍💻 Auteur

**Mohamed Zaidi**
