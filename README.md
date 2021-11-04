# SITE PIZ’AIOLI
## Description :
* Fournir un site internet de service de commande de pizza. Au départ le site sera un site pour une seule enseigne. Il va proposer de commander des pizzas et va fournir le temps d’attente.
1. Couche présentation :
Se baser sur une interface ergonomique flat design, correspondante à l’actualité.
a. Web design :
- Comme tous les sites actuels, respectez les codes couleurs imposés par le client (ici les couleurs du drapeau italien)
b. Informations :
- Liste des pizzas classées par couleur et par dimensions
- Ingrédients de chaque pizza
- Prix des pizzas
-
c. Extras :
- Utilisation du préprocesseur css
- Utilisation d’un FW css
- Utilisation d’un modèle MVVM (angularjs / knockoutJS / jQuery)
2. Couche métier :
La couche métier correspond aux interactions que va avoir l’utilisateur avec le site selon ses privilèges. Dans cette couche est intégré les traitements internes à l’application. Les commandes sont faites par les clients, puis sont sauvegardées en base de données.
Le client a une interface qui liste en temps réel les commandes. Il peut agir dessus afin de faire évoluer le statu.
L’application calcule le temps d’attente des commandes grâce à la formule suivante : E=MC². Où M est égal à la capacité du four divisée par le poids de la mozzarella et c’est est la vitesse maximale de la mobylette du livreur.
a. Le visiteur :
Le visiteur à un accès de consultation sur le site. Il peut :
- Afficher les pages du site
- Se connecter
- S’inscrire
- Commander les pizzas
b. Le client (admin) :
Le client (les pizzaiolos) à un accès en CRUD sur toutes les informations du site. Il ne peut pas toucher à l’ergonomie.
- Il a les mêmes privilèges que le visiteur
- Il a accès à une page d’administration
- De manière générale interagît en CRUD sur TOUTES les informations
1. Liste des pizzas
2. Détails des pizzas
- Gestion commandes
-
c. Consommateur :
Gestion des web services (à définir)
d. Clients :
Les clients auront un accès avec les privilèges des visiteurs, ils pourront bénéficier des avantages des utilisateurs connectés sur le site.
- Commande hebdo
- Commande rapide

3. Couche persistance :
La couche persistance correspond aux informations stockées en base de données. On essayera le plus possible d’utiliser les jointures afin de bien séparer les données entre elles.
a. Utilisateurs :
Les utilisateurs se différencieront par un mélange entre leur nature et leur rôle au sein de l’application
- Administrateurs (pizzaiolo)
- Clients (utilisateurs enregistrés)
- Consommateurs (web services)
b. Données :
Les données correspondent aux informations variables du site. Liste des données :
- Adresse du shop
- Presentation
- Pédigré
- Commande
- Pizza
- Message
- Ingrédient

4. Gestion du projet :
Il est défini comme étant la somme de deux parties : celle obligatoire, et la facultative.
a. Partie obligatoire :
La partie obligatoire doit permettre de fournir au pizzaiolo, une visibilité sur le web, avec la possibilité de commander en ligne. Il DOIT pouvoir gérer les commandes a travers son interface.
b. Partie facultative :
La partie facultative (à définir).
5. ANNEXES :
Ici nous auront les diagrammes et les liens vers les outils afin de pouvoir coder.
a. Dossier des ressources partagées
b. Carnet de bord
c. Trello
d. Github
