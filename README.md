# Projet d'Analyse de Données Commerciales

## 1. Introduction  
Ce projet a pour objectif de réaliser une analyse exploratoire, statistique et visuelle des données de ventes contenues dans un fichier Excel. L'objectif est d'en extraire des informations clés pour comprendre la performance de l'entreprise : ventes, bénéfices, marges, comportement des clients, etc. Le projet suit une approche data-driven en utilisant Python et ses bibliothèques dédiées à la data science.

## 2. Présentation des Données  
Les données proviennent du fichier `Sales.xlsx` et contiennent les colonnes suivantes :  
- **Order Date** : Date de commande  
- **Sales** : Montant des ventes  
- **Profit** : Bénéfice généré  
- **Order Quantity** : Quantité commandée  
- **Customer Name** : Nom du client  
- **City** : Ville  
- **Sales Channel** : Canal de vente (ex: En ligne, Magasin)  
- **Product Name** : Nom du produit  

## 3. Méthodologie  
L'analyse a été réalisée selon les étapes suivantes :  

### Nettoyage des Données  
- Suppression des doublons  
- Gestion des valeurs manquantes  
- Conversion des formats de date  

### Création de Variables  
- Ajout de colonnes dérivées :  
  - Année  
  - Mois  
  - Jour de la semaine  

### Calcul des Indicateurs Clés  
- Calcul des KPIs :  
  - Ventes totales  
  - Bénéfices totaux  
  - Marges bénéficiaires  
  - Variation annuelle  

### Création d'une Table des Dates  
- Construction d'une table dédiée pour une meilleure organisation temporelle  

### Visualisation des Données  
Création de visualisations pour :  
- Comparaisons annuelles  
- Analyse par client  
- Performance par ville  
- Performance par canal de vente  
- Performance par produit  

## 4. Technologies Utilisées  
- Python  
- Pandas (Manipulation des données)  
- Matplotlib/Seaborn (Visualisation)  
- Jupyter Notebook (Analyse interactive)
- Visual Studio Code (Editeur de code)

## 5. Comment Exécuter le Projet  
1. Cloner ce dépôt :  
   ```bash
   git clone https://github.com/Ilyas11-03/Mini_Projet_Python.git
  Ou bien tu peux juste télécharger le fichier zip.
