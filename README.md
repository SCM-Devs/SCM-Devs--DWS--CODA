# SCM DEV_CODA_DWS
  Voici la première version de l'application de recherche pour l'entreprise DWS.
Cette application peut fonctionner sans internet.
Cette version dispose d'une image par défaut pour tous les produits, et vous ne pourrez pas modifier les produits. Ces fonctionnalités, ainsi que d'autres, seront ajoutées dans la prochaine version.

#### 🔧 Pour l'installer :
- Vous devez prendre le code sur un ordinateur.
- Installer python sur l'ordinateur ( ou prendre un ordinateur qui la déjà d'installer déjà ).
- Ajouter les dépendances avec : `pip install -r requirements.txt` .
- Placer une image par défaut nommée "image.webp" dans app/static/images/ .
- Lancer l'appli avec `python run.py`
- Puis voir le résultat dans un navigateur avec `http://localhost:5000` .

#### 👉 Sur l'appli vous pouvez -->
- Rechercher un produit par son nom.
- Le visualiser en cliquant dessus pour voir sa fiche produit.
- Revenir sur la page de recherche et recommencer !

#### 📍 Le Principe ?
  Nous avons développé un bot de scraping qui récupère les produits du site Extime.com, dans les catégories parfums et cave.
  Ensuite, les données récupérées sont stockées dans un fichier au format CSV, que nous utilisons pour afficher les produits dans l'application.

L'application gère les produits et leurs attributs afin d'offrir une expérience utilisateur agréable. Nous avons fait de notre mieux pour nous mettre à la place de l'utilisateur et optimiser son utilisation.
