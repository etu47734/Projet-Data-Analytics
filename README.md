# Projet-Data-Analytics
## Membres du groupe
-   Colin Hugo (etu47734@henallux.be)
-   Marchand Matthias (etu49363@henallux.be)
-   Roelens William (etu48638@henallux.be)

## Structure du dossier
```
.  
├── financial_transactions/  
│   ├── transactions_data.csv  
└── init.ipynb
```
Pour utiliser le projet, [télécharger le dataset modifié](https://henallux-my.sharepoint.com/:x:/g/personal/etu47734_henallux_be/EVvNvbXaKRBFlcmoYAJD5akBuZ-e5XhHCQBhQFnbFR83vQ?e=AaOMES) depuis github
Et extraire le fichier .csv dans un dossier nommé `financial_transactions`.  
Les fichiers .json ne sont pas utiles pour ce projet.  
Note: Le fichier `transactions_data.csv` contenant ~13.000.000 lignes, nous avons décidés de le tronquer et de ne garder que celles qui concernent l'année 2010 (1.240.881 premières)
La source originale du dataset vient de [Kaggle](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets?resource=download)

## Installation
```
pip install pandas
pip install matplotlib
pip install seaborn
```