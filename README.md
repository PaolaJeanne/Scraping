

## choix d'un outil de creation



#### 1.Venv
Outil standard de Python


#### 2.virtualenv:

 Outil externe plus ancien mais largement utilisé.
#### Executer la commande:

#### 1. Venv

python -m venv mon_environnement
#### 2.Virtualenv

python -m venv mon_environnement
#### NB: Remplacer mon_environnement par le nom que vous souhaitez donner a votre environnement
## Activation de l'environnement virtuel :


#### 1.Sur Unix/macOS:

 source mon_environnement/bin/activate

#### 2.Sur Windows :

 mon_environnement\Scripts\activate
## Scrapings

## Les étapes clés du web scraping
#### 1.Identifier les données à extraire (Définir les objectifs) :

Quels types de données souhaitez-vous récupérer (textes, images, liens, etc.) ? Analyser la structure du site: Utiliser les outils de développement du navigateur pour inspecter le code HTML et comprendre comment les données sont organisées.
#### 2.Choisir un outil de scraping:

Bibliothèques Python: BeautifulSoup, Scrapy, Selenium sont les plus populaires. Elles permettent de naviguer dans le DOM (Document Object Model) et d'extraire les informations.

Outils visuels: Certains outils comme ParseHub ou Import.io offrent une interface graphique pour créer des extractions sans écrire de code. API: Si le site propose une API, il est souvent plus efficace et respectueux des conditions d'utilisation de l'utiliser.
#### 3.Écrire le script de scraping:

Importer les bibliothèques: Charger les bibliothèques nécessaires (requests, BeautifulSoup, etc.). Faire une requête HTTP: Utiliser la bibliothèque requests pour envoyer une requête au serveur et récupérer le contenu de la page. Parser le HTML: Utiliser BeautifulSoup pour analyser le code HTML et extraire les données souhaitées.
#### 4.Stocker les données :

Enregistrer les données dans un fichier CSV, JSON, ou une base de données.
