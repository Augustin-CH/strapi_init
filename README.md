# Strapi application

# INSTALLATION #
- executer cette commande dans le dossier choisis : git clone https://github.com/Augustin-CH/strapi_init.git
- installer strapi : yarn add strapi

# LANCER LE SERVEUR #
- lancer le serveur : yarn develop
- la premiere fois il faudra créer un compte administrateur

# BASE DE DONNEES #
La base est constituée de 3 tables :
- User : regroupe les differents utilisateurs inscrits
- Products : regroupe les produits disponibles, leurs quantités, prix, description et image
- Orders : historise les commandes passées, par qui, de quels produits, à quelle date

# REQUETE API #
La requete "GET http://localhost:1337/orders" affichera les differentes commandes, les produits qu'elles contenaients ainsi que les informations des utilisateurs les ayants passées.

On pourra appliquer ces diffenrents parametres pour trier, filtrer, choisir l'ordre d'affichage etc :
https://strapi.io/documentation/3.0.0-beta.x/content-api/parameters.html#available-operators

