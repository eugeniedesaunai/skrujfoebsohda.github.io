# HTML-CSS-PHP-SQL – Projet « Food & Drink »
## Objectif pour l'apprenant
Mettre en œuvre les capacités acquises en cours de formation en réinvestissant ce qui a été appris en situation professionnelle en lien avec un besoin formulé.

## Modalités
Collaboration en binômes demandée.  

## Gestion de la communication
-   Réalisez un point de 5 minutes en début de chaque demi-journée pour définir vos objectifs d'avancement.    
-   Enregistrez un rapport d'activité, avec la répartition des tâches.
-   Centralisez vos questions techniques en fin de journée auprès des délégués

## Présentation du projet

### Objet du document
Ce document s'adresse à une équipe de développeurs d'applications web en première année de formation

### Descriptions des parties prenantes
-   Client / Chef de projet : Service pédagogique
-   Développeur : Etudiant en 1e année

### Objectifs

_Il s’agit d’un projet fictif, toute relation avec un projet existant ne serait que fortuite._

Le restaurant « Food and Drink » situé à Rennes, souhaite informatiser leurs services en affichant leur menu en ligne et ainsi permettre de fidéliser un plus grand nombre de personnes. 

Dans l'idéal, le gérant du restaurant souhaiterait faire un site web en PHP en lien avec une base de données en MySQL.

L’établissement se vante de travailler uniquement des produits de saison avec des producteurs locaux et souhaite également les mettre à l’honneur.

Le site devra présenter à minima :
-   L’adresse, numéro de téléphone et la localisation du restaurant
-   Une zone permettant de préciser les valeurs de l’enseigne
-   Les menus du restaurant
-   Une liste des producteurs locaux
-   Une liste de leurs références (Gault & Millau, TripAdvisor, Guide Michelin)

### Description

Le site doit avoir :
-   Une partie client (front end)
-   (Optionnel) : Une partie administration (back end)

#### Le Front End

La partie cliente quant à elle doit être en SPA (Single Page Application) et présenter :
-   Le nom, le logo, l’adresse et le numéro de téléphone de l’établissement
-   La localisation du restaurant (encadré avec un maps – google ou open street maps)
-   Une zone permettant de préciser les valeurs de l’enseigne
-   Les menus du restaurant
-   Une liste des producteurs locaux
-   Une liste de leurs références (Gault & Millau, TripAdvisor, Guide Michelin)
-   Une barre de menu permettant de naviguer directement à différentes sections
-   Un formulaire de contacts

Le formulaire de contacts doit contenir les champs suivants :
-   Nom
-   Email de contact (facultatif)
-   Objet du mail
L’envoi réel du mail est optionnel.

#### Le Back End
Partie optionnelle pour ceux ayant déjà résolu la première partie. 

La partie administration doit avoir recours à une authentification réalisée par le biais d’un fichier htpasswd. Au sein de ce back end, il sera possible d’administrer les menus. Ces derniers changent au fil des saisons et des produits disponibles.

Un menu est composé d’un nom, d’une entrée, d’un plat, d’un dessert, d’une boisson ainsi que d’un tarif en euros.

La partie administration doit permettre l’ajout, la visualisation et la modification d’un menu.

L’interface donnera l’illusion de pouvoir supprimer un menu, mais en réalité le menu restera conservé en base de données.

Un filtre doit être mis en place permettant d’afficher ou non les anciens menus. Une fois qu’un menu a été « supprimé », il ne pourra plus jamais être « réactivé » mais sera consultable à des fins de statistiques et de suivi.

Concernant les producteurs locaux, l’établissement travaille depuis des années avec les mêmes producteurs, dans un premier temps il ne requiert pas de pouvoir modifier ces fournisseurs.


### Contraintes techniques
Si la partie back est implémentée, elle devra être développée en PHP, en lien avec une base de données MySQL/MariaDB.

### Description de l'existant
Un logo :
-   food-and-drink.svg (présent au sein de ce dépôt)

Une adresse : 
 - 3 Rue de la Chalotais, 35000 Rennes

Une liste de producteurs locaux :
-   Les amis de la ferme (https://www.amisdelaferme.fr/)
-   Les jardins du châtaigner ([https://www.cueillette-bio-rennes.fr/](https://www.cueillette-bio-rennes.fr/))
-   Maison gesbert (http://www.maisongesbert.com)
    
Une liste de références :
-   Gault et Millau (https://fr.gaultmillau.com/)
-   Michelin (https://guide.michelin.com/fr/fr)
-   Trip Advisor (https://www.tripadvisor.fr/)
    
Un exemple de menu :
-   Menu “Légumes” : 54 €
    -   Carpaccio de betteraves marinées au soja et gingembre
    -   Tourte feuilletée – céleri et truffe, jus concentré de légumes
    -   Topi noisettes – topinambour poché au sirop, condiment passion , crème glacée noisette
    -   Vin rouge Ventoux – Les grains marsellan 2015
        
-   Menu « Au rythme des saisons » : 71€
    -   Foie-gras mi-cuit au sichuan
    -   Turbot rôti au ras el-hanout, chou-fleur et choux de bruxelles
    -   Agrumes – crème diplomate au citron, pesto à l’estragon
    -   Bourgogne Pinot noir 2017
        

### Critères d'acceptabilité du produit
-   Le(s) document(s) livrés doivent être respectueux de la RGPD.
-   Le(s) document(s) livrés doivent être responsive
    

### Analyse non fonctionnelle
-   Votre application doit être accessible en français au minimum
-   L'application doit s'adapter aux différents supports informatiques (responsive)
    
### La méthodologie à appliquer

-   Etape 1 : Analyse préliminaire
    -   Questions complémentaires
    -   Définition des besoins
    -   Répartition des rôles au sein de vos équipes.
    
-   Etape 2 : Maquettage
    -   Conception des zonings et maquettes de votre application
    -   Premier jet de l’Interface en HTML et CSS

-   Etape 3 (Optionnel): Conception de la BDD
    -   Elaboration du MCD
    -   Création de la BDD pour MySQL
    
-   Etape 4 (Optionnel): Back Office
    -   Depuis la page d’administration, pouvoir gérer les menus, activer ou non le filtre
    
-   Etape 5 : Front Office
    -   Le client a la possibilité de :
        -   Visualiser les menus actifs
        -   Contacter le restaurant
            
-   Etape 6 : Améliorations
    - Accessibilité
    - Responsive
  

### Les livrables du projet

Le rendu doit être réalisé sous forme d’un dépôt GIT, il devra contenir :
- Un fichier README.md expliquant le projet, le contexte de ce sujet, les membres ayant contribué au projet
-   Les zonings et maquettes de l’application
-   Le code de l’application finalisée et refactorée
-   Optionnel : Le MCD de la base de données
-   Optionnel : La structure de la base de données
-   Optionnel : Les données de la base de données
-   Optionnel : Les identifiants requis pour se connecter au back office .

### Conseils
-   Réfléchissez et concertez-vous avant d’avancer sur le sujet.
-   Vous pouvez utiliser des frameworks.
-   Attention à vos identifiants pour la base de données ou pour accéder à la partie back office. Ils devront être modifiables ou à défaut communiquées au formateur.
-   Le contenu que vous intégrerez devra être travaillé, soigné et professionnel.
-   Travailler à plusieurs est difficile, concertez-vous et privilégiez le pair programming. 


<img src='https://i1.wp.com/retromatti.com/wp-content/uploads/2019/12/baby-yoda-in-pod.png?fit=128,128' >


# Food-and-Drink

![Food and Drink](https://user-images.githubusercontent.com/108462777/176671337-94ba686f-c9c9-4a98-85e4-001ef1479565.png)

![iPhone_11_Pro_Max_-_1](https://user-images.githubusercontent.com/108462777/176671672-9ab6af59-1816-46be-ba8c-cb169258c3f1.png)
