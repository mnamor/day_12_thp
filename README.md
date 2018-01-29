# Ruby on![alt text][logo]

## 1 Les site statique et dynamique

Un site statique peut être HTML comme Flash. Ce n'est pas parce que ca bouge que c'est dynamique.

Le site statique est composé d'un contenu défini (texte, son, vidéo, anim flash,...)
mais non modifiable à moins de plonger dans le code. De même, sur un site statique, chacun a droit au même contenu.
La page sera identique pour tout le monde. Enfin, aucune interaction avec le serveur ne se fera.
Un visiteur demande la page statique, le serveur lui envoit la page demandée, point barre.

Ceci est à mettre en opposition à un site dit "dynamique" qui s'adapte à ses utilisateurs. Par exemple, sur ce Forum,
tu t'es logué pour pouvoir écrire ce message. Tu as demandé au serveur et au language dynamique de te loguer.
(dans le cas ici présent, PHP).
Le language dynamique te permet de faire varier le contenu des pages en fonction des visiteurs. Pour l'utilisateur A,
bah son login sera A, et pour B, le login sera B, pourtant la page de login elle sera la même.
Les sites dynamiques ne le sont que parce qu'ils utilisent des languages de programmation dynamiques.
Sur un site dynamique, il y a souvent également une interraction avec une base de données
(par le biais du language dynamique employé).

Aparament Ruby on Rail (RoR) te permet de fair un site dynamique directement sans passer par la phase statique.

## 2 Le MVC

Modèle-vue-contrôleur ou MVC est un motif d'architecture logicielle destiné aux interfaces graphiques,
lancé en 1978 et très populaire pour les applications web.
Le motif est composé de trois types de modules ayant trois responsabilités différentes :
les modèles, les vues et les contrôleurs.

    Un modèle (Model) contient les données.
    Une vue (View) contient la présentation de l'interface graphique.
    Un contrôleur (Controller) contient la logique concernant les actions effectuées par l'utilisateur.

Ce motif est utilisé par de nombreux frameworks pour applications web tels que Ruby on Rails,
Django, ASP.NET MVC, Spring, Struts, Symfony, Apache Tapestry ou Angular Js.

## 3 Les routes en Ruby On Rails

Les routes permettent d’interpréter les URL et d’orienter vers les bonnes actions des controlleurs.
La configuration se trouve dans le fichier config/routes.rb .

*lien: très intérèsent:* [Routes](https://www.sois-net.fr/routes-ruby-on-rails/)

## 4 Les Bases de Données

Une base de données (database en anglais),
permet de stocker et de retrouver l'intégralité de données brutes ou d'informations en rapport avec un thème ou une activité ;
celles-ci peuvent être de natures différentes et plus ou moins reliées entre elles. Dans la très grande majorité des cas,
ces informations sont très structurées, et la base est localisée dans un même lieu et sur un même support.
Ce dernier est généralement informatisé.

La base de données est au centre des dispositifs informatiques de collecte, mise en forme,
stockage et utilisation d'informations. Le dispositif comporte un système de gestion de base de données (abréviation : SGBD):
un logiciel moteur qui manipule la base de données et dirige l'accès à son contenu.
De tels dispositifs — souvent appelés base de données — comportent également des logiciels applicatifs,
et un ensemble de règles relatives à l'accès et l'utilisation des informations.

La manipulation de données est une des utilisations les plus courantes des ordinateurs.
Les bases de données sont par exemple utilisées dans les secteurs de la finance, des assurances,
des écoles, de l'épidémiologie, de l'administration publique (notamment les statistiques) et des médias.

Lorsque plusieurs choses appelées bases de données sont constituées sous forme de collection,
on parle alors d'une banque de données.

## 5 Get/Post

Les deux méthodes HTTP les plus utilisées sont: GET et POST.

Deux méthodes couramment utilisées pour une requête-réponse entre un client et un serveur sont: GET et POST.

    GET - Demande des données d'une ressource spécifiée
    POST - Soumet les données à traiter à une ressource spécifiée

* La méthode GET

Notez que la chaîne de requête (paires nom / valeur) est envoyée dans l'URL d'une requête GET:
/test/demo_form.php?name1=value1&name2=value2

Quelques autres notes sur les requêtes GET:

    Les requêtes GET peuvent être mises en cache
    Les requêtes GET restent dans l'historique du navigateur
    Les requêtes GET peuvent être mises en signet
    Les requêtes GET ne doivent jamais être utilisées avec des données sensibles
    Les requêtes GET ont des restrictions de longueur
    Les requêtes GET ne doivent être utilisées que pour extraire des données

* La méthode POST

Notez que la chaîne de requête (paires nom / valeur) est envoyée dans le corps du message HTTP d'une requête POST:
POST /test/demo_form.php HTTP / 1.1
Hôte: w3schools.com
nom1 = valeur1 & nom2 = valeur2

Quelques autres notes sur les requêtes POST:

    Les requêtes POST ne sont jamais mises en cache
    Les requêtes POST ne restent pas dans l'historique du navigateur
    Les requêtes POST ne peuvent pas être mises en signet
    Les requêtes POST n'ont aucune restriction sur la longueur des données

## 6 Les concepts de migration.

Les migration serve à faire évoluer la base de donné,
afin que les importes de ficher et les modification du site ou l'application soi plus simple à comprendre,
pour les différents dévelopeurs et de simplifier la mise en ligne.

ces modification  son contenue dans le dossier DB.

## 7 Les relations entre les models des BDD.

Le modèle relationnel est une manière de modéliser les relations existantes entre plusieurs informations,
et de les ordonner entre elles. Cette modélisation qui repose sur des principes mathématiques mis en avant par E.F.
Codd est souvent retranscrite physiquement (« implémentée ») dans une base de données.

## 8 Les fonctions du CRUD

L'acronyme informatique anglais CRUD (pour create, read, update, delete) (parfois appelé SCRUD avec un "S" pour search)
désigne les quatre opérations de base pour la persistance des données,en particulier le stockage d'informations en base de données.

_Soit:_

    create : créer
    read   : lire
    update : mettre à jour
    delete : supprimer

Plus généralement, il désigne les opérations permettant la gestion d'une collection d'éléments.

Ce terme est aussi un jeu de mot en anglais sur l'adjectif crude (en français brut ou rudimentaire).

    
*Ecrit par* ~ M-NaM ~

[logo]: https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Ruby_On_Rails_Logo.svg/200px-Ruby_On_Rails_Logo.svg.png "Ruby On Rails"
