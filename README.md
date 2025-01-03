# Projet-Data-Analytics
## Membres du groupe
-   Colin Hugo (etu47734@henallux.be)
-   Marchand Matthias (etu49363@henallux.be)
-   Roelens William (etu48638@henallux.be)

## Structure du dossier
```
.  
├── financial_transactions/  
│   ├── cards_data.csv  
│   ├── transactions_data.csv  
│   └── users_data.csv  
└── fichiers pythons
```
Pour utiliser le projet, [télécharger le dataset modifié](https://github.com/etu47734/Projet-Data-Analytics/blob/main/financial_transactions.zip) depuis github
Et extraire les fichiers .csv dans un dossier nommé `financial_transactions`.  
Les fichiers .json ne sont pas utiles pour ce projet.  
Note: Le fichier `transactions_data.csv` contenant ~13.000.000 lignes, nous avons décidés de le tronquer et de ne garder que les 100.000 premières. 
La source originale du dataset vient de [Kaggle](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets?resource=download)

## Installation
```
pip install pandas
```