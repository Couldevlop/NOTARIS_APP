# NOTARIS_APP 

# Presentation du projet
NotarisApp est un projet  de gestion de cabinet notaire.
Il est constitué deux trois parties:

*  Le back-end
   - des API développées en Java 17 + springboot 3
   - Keycloack(Pour la partie authentification): en production
   - Firebase(pour l'authentification) en test
*   Le front-end
   - développé en angular 15/16

* Base de données
   - Mysql

Toutes ces applications sont encapsulée dans une image docker qui elle meme est constituée des images de chacune des parties de l'application.
Ce qui veut dire que l'image de NotarisApp = image(notaris-api + notaris-ui + mysql + keycloak)

# Mode d'emploie
