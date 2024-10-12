
## Installation

Comment crée un environnement virtuel:

##choisir un outil

venv: Outil standard de Python.

virtualenv: Outil externe plus ancien mais largement utilisé.

##Exécuter la commande:

Avec venv:
python -m venv mon_environnement

Avec virtualenv:
virtualenv mon_environnement
 
NB: remplacer mon_environnement par le nom que vous souhaitez donner a votre environnement

Activer l'environnement virtuel:

#Sur Unix/macOS:
 source mon_environnement/bin/activate

#Sur Windows: 
mon_environnement\Scripts\activate
    
## Scrapings
Les étapes clés du web scraping

#Identifier les données à extraire(Définir les objectifs):

Quels types de données souhaitez-vous récupérer (textes, images, liens, etc.) ? Analyser la structure du site: Utiliser les outils de développement du navigateur pour inspecter le code HTML et comprendre comment les données sont organisées.

#Choisir un outil de scraping:

Bibliothèques Python: BeautifulSoup, Scrapy, Selenium sont les plus populaires. Elles permettent de naviguer dans le DOM (Document Object Model) et d'extraire les informations.

 Outils visuels: Certains outils comme ParseHub ou Import.io offrent une interface graphique pour créer des extractions sans écrire de code. API: Si le site propose une API, il est souvent plus efficace et respectueux des conditions d'utilisation de l'utiliser.

#Écrire le script de scraping:

Importer les bibliothèques: Charger les bibliothèques nécessaires (requests, BeautifulSoup, etc.). Faire une requête HTTP: Utiliser la bibliothèque requests pour envoyer une requête au serveur et récupérer le contenu de la page. Parser le HTML: Utiliser BeautifulSoup pour analyser le code HTML et extraire les données souhaitées.

#Stocker les données:

Enregistrer les données dans un fichier CSV, JSON, ou une base de données.
