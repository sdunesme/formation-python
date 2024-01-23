# Formation Python pour les géographes

Support de formation Python pour les géographes préparé par Samuel Dunesme.

## Guide de démarrage
### Installation de l'environnement

La première fois, vous devez installer un environnement python avec toutes les librairies dont nous allons avoir besoin pendant ce cours.
Ouvrez un PowerShell dans le dossier contenant ce cours et tapez les commandes suivantes :

```powershell
# Création de l'environnement
C:/<chemin_installation_python>/python.exe -m venv env --prompt formation-python

# Activation de l'environnement créé
.\env\Scripts\activate

# Mise à jour du gestionnaire de paquets
.\env\Scripts\python.exe -m pip install -U pip

# Installation des paquets nécessaires au cours
.\env\Scripts\python.exe -m pip install numpy matplotlib pyarrow pandas geopandas rasterio contextily folium mapclassify jupyterlab
```

### Activation de l'environnement et lancement de l'IDE

Lors des prochaines séances, votre environnement est déjà installé. Vous n'aurez plus qu'à l'activer comme ceci.
Ouvrez un PowerShell dans le dossier contenant ce cours et tapez les commandes suivantes :

```powershell
# Activation de l'environnement créé
.\env\Scripts\activate

# Lancement de l'IDE Jupyter-Lab
jupyter-lab.exe
```

### Suivi du cours

Dans ce cours, vous trouverez des cellules de code pré-remplies. C'est à vous de les exécuter pour voir le résultat. A tout moment, vous êtes encouragés à copier ces cellules, les modifier, et observer les résultats pour bien comprendre ce qui s'y passe. 

D'autres cellules ne sont pas pré-remplies ou incomplètes : il s'agit des exercices signalés par un ✍️.
