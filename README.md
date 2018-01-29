Peer-teaching

Les site statique et dynamique

Tout d'abord, ma réponse ne correspond pas forcément à une définition "stricte" de la différence.
C'est plus la manière dont je la vois, même si les principes sont les mêmes.

Un site statique peut être HTML comme Flash. Ce n'est pas parce que ca bouge que c'est dynamique,
(du moins pas au sens selon lequel je l'entends).

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

Tu peux ainsi mettre en opposition HTML et PHP.

Mais en gros c'est l'idée du site qui s'adapte et bouge dans le sens de son contenu qui fait qu'un site est dynamique ou non.
Pas parce que tu as une animation Flash dans une bannière.

Maintenant, que recommander entre les 2? Ils sont complémentaires.
Il faut commencer par du "statique" et bien connaître xHTML/CSS, et ensuite tu pourras ajouter du dynamisme avec du PHP/MySQL,
par exemple.
Un site dynamique est évidemment beaucoup plus attractif de par son mouvement perpetuel,
mais il aura quand même besoin de composants statiques. Tu ne sais donc pas faire de PHP si tu ne connais rien de l'xHTML.
(partiellement vrai cette dernière affirmation mais bon... partons sur des bases saines).

Aparament Ruby on Rail (RoR) te permet de fair un site dynamique directement sans passer par la phase statique.

Le MVC

Modèle-vue-contrôleur ou MVC est un motif d'architecture logicielle destiné aux interfaces graphiques,
lancé en 1978 et très populaire pour les applications web.
Le motif est composé de trois types de modules ayant trois responsabilités différentes :
les modèles, les vues et les contrôleurs.

    _Un modèle_ ( *Model* ) contient les données à afficher.
    _Une vue_ ( *View* ) contient la présentation de l'interface graphique.
    _Un contrôleur_ ( *Controller* ) contient la logique concernant les actions effectuées par l'utilisateur.

Ce motif est utilisé par de nombreux frameworks pour applications web tels que Ruby on Rails,
Django, ASP.NET MVC, Spring, Struts, Symfony, Apache Tapestry ou Angular Js.

Les routes en Ruby On Rails

Les routes permettent d’interpréter les URL et d’orienter vers les bonnes actions des controlleurs.
La configuration se trouve dans le fichier config/routes.rb .

*lien: tres intéresent:* [Routes](https://www.sois-net.fr/routes-ruby-on-rails/)

Les Bases de Données

Une base de données (database en anglais),
permet de stocker et de retrouver l'intégralité de données brutes ou d'informations en rapport avec un thème ou une activité ;
celles-ci peuvent être de natures différentes et plus ou moins reliées entre elles1,2. Dans la très grande majorité des cas,
ces informations sont très structurées, et la base est localisée dans un même lieu et sur un même support.
Ce dernier est généralement informatisé.

La base de données est au centre des dispositifs informatiques de collecte, mise en forme,
stockage et utilisation d'informations. Le dispositif comporte un système de gestion de base de données (abréviation : SGBD):
un logiciel moteur qui manipule la base de données et dirige l'accès à son contenu.
De tels dispositifs — souvent appelés base de données — comportent également des logiciels applicatifs,
et un ensemble de règles relatives à l'accès et l'utilisation des informations2.

La manipulation de données est une des utilisations les plus courantes des ordinateurs.
Les bases de données sont par exemple utilisées dans les secteurs de la finance, des assurances,
des écoles, de l'épidémiologie, de l'administration publique (notamment les statistiques) et des médias.

Lorsque plusieurs choses appelées bases de données sont constituées sous forme de collection,
on parle alors d'une banque de données.

Get/Post

Les deux méthodes HTTP les plus utilisées sont: GET et POST.
Qu'est-ce que HTTP?

Le protocole HTTP (*Hypertext Transfer Protocol*) est conçu pour permettre les communications entre les clients et les serveurs.

HTTP fonctionne comme un protocole de requête-réponse entre un client et un serveur.

Un navigateur Web peut être le client et une application sur un ordinateur hébergeant un site Web peut être le serveur.

Exemple: Un client (navigateur) soumet une requête HTTP au serveur; alors le serveur renvoie une réponse au client.
La réponse contient des informations d'état sur la demande et peut également contenir le contenu demandé.
Deux méthodes de requête HTTP: GET et POST

Deux méthodes couramment utilisées pour une requête-réponse entre un client et un serveur sont: GET et POST.

    GET - Demande des données d'une ressource spécifiée
    POST - Soumet les données à traiter à une ressource spécifiée

La méthode GET

Notez que la chaîne de requête (paires nom / valeur) est envoyée dans l'URL d'une requête GET:
/test/demo_form.php?name1=value1&name2=value2

Quelques autres notes sur les requêtes GET:

    Les requêtes GET peuvent être mises en cache
    Les requêtes GET restent dans l'historique du navigateur
    Les requêtes GET peuvent être mises en signet
    Les requêtes GET ne doivent jamais être utilisées avec des données sensibles
    Les requêtes GET ont des restrictions de longueur
    Les requêtes GET ne doivent être utilisées que pour extraire des données

La méthode POST

Notez que la chaîne de requête (paires nom / valeur) est envoyée dans le corps du message HTTP d'une requête POST:
POST /test/demo_form.php HTTP / 1.1
Hôte: w3schools.com
nom1 = valeur1 & nom2 = valeur2

Quelques autres notes sur les requêtes POST:

    Les requêtes POST ne sont jamais mises en cache
    Les requêtes POST ne restent pas dans l'historique du navigateur
    Les requêtes POST ne peuvent pas être mises en signet
    Les requêtes POST n'ont aucune restriction sur la longueur des données

Les concept de migration.

Les migration serve à faire évoluer la base de donné,
afin que les importes de ficher et les modification du site ou l'application soi plus simple à comprendre,
pour les différent dévelopeur et de simplifier la mise en ligne.

cet modification  son contenue dans le dossier DB.

Les relations entre les models des BDD.

Le modèle relationnel est une manière de modéliser les relations existantes entre plusieurs informations,
et de les ordonner entre elles. Cette modélisation qui repose sur des principes mathématiques mis en avant par E.F.
Codd est souvent retranscrite physiquement (« implémentée ») dans une base de données.

Brève description.

On appelle « relation » un ensemble d'attributs qui caractérisent une proposition ou une combinaison de propositions comme
"un employé a un matricule, il a un nom, il a un employeur". Dans cet exemple, les attributs de l'employé sont : son matricule,
son nom et son employeur. Chaque combinaison de propositions ainsi formée est appelée tuple ou collection ordonnée d'objets.
Par exemple l'ensemble ("1245", "Jean Dupond", "Compagnie des belles lettres") constitue un tuple de relation "employé".
Les relations sont d'ordinaire représentées sous la forme de tables. Dans l'exemple précédent, la table serait libellée "employé".
Usuellement, les praticiens accordent la même signification aux concepts de "relation" et de "table". De même,
ils assimilent d'une part la "ligne dans la table" et le tuple, et d'autre part le "libellé de colonne dans la table" et l'attribut.
Par définition, chaque tuple d'une relation est unique. Il est identifié par un attribut
(un identifiant unique appelé "clef primaire") ou une combinaison de plusieurs attributs qui forme la clef.
L'ordre des tuples n'est pas significatif.

Codd a défini une algèbre relationnelle et des opérateurs qui permettent de construire de nouvelles relations en combinant des relations préalablement définies.
Les idées de Codd ont été implémentées -- plus ou moins fidèlement -- dans les systèmes de gestion des bases de données relationnelles
ou SGBDR telles que le projet expérimental IBM System R, puis des produits commerciaux tels qu'Oracle, DB2 ou MySQL, et dans le langage de manipulation des données SQL.

Le modèle relationnel est aujourd’hui l'un des modèles les plus utilisés. « Les premiers systèmes de gestion de base de données
(SGBD ou DBMS en anglais) bâtis sur ce modèle ont été SQL/DS et DB2 de IBM,
d'où est né le langage de manipulation de bases relationnelles, SQL (Structured Query Language).
»1 Le modèle relationnel est basé sur deux instruments puissants : l’algèbre relationnelle
(c'est-à-dire le concept mathématique de relation en théorie des ensembles)
et la notion de produit cartésien. Ce modèle définit une façon de représenter les données,
les opérations qui peuvent être effectuées ainsi que les mécanismes pour préserver la consistance des données.
E.F Codd a décrit les principes et la conception de modèle relationnel dans son livre
« A relational model of data for large shared data banks ».

Les fonctions du CRUD

L'acronyme informatique anglais CRUD (pour create, read, update, delete) (parfois appelé SCRUD avec un "S" pour search)
désigne les quatre opérations de base pour la persistance des données,en particulier le stockage d'informations en base de données.

_Soit:_

    *create* : créer
    *read* : lire
    *update* : mettre à jour
    *delete* : supprimer

Plus généralement, il désigne les opérations permettant la gestion d'une collection d'éléments.

Ce terme est aussi un jeu de mot en anglais sur l'adjectif crude (en français brut ou rudimentaire).

Voir aussi les noms:  
[REST](https://fr.wikipedia.org/wiki/Representational_state_transfer)  
[RESTful](https://fr.wikipedia.org/wiki/Representational_state_transfer)  
[HATEOAS](https://fr.wikipedia.org/wiki/HATEOAS)  
ou [http://putaindecode.io/fr/articles/api/hateoas/](http://putaindecode.io/fr/articles/api/hateoas/)   

Application dans les bases de données

L'acronyme CRUD se réfère à la majorité des opérations implémentées dans les bases de données relationnelles.
Chaque composante de l'acronyme peut être associé à un type de requête en SQL ainsi qu'à une méthode HTTP
Operation 	SQL 	HTTP
Create 	INSERT 	POST (en)
Read (Retrieve) 	SELECT 	GET (en)
Update (Modify) 	UPDATE 	PUT (en)
Delete (Destroy) 	DELETE 	DELETE (en)
Utilisation dans les interfaces logicielles

Par *exemple*, une application carnet d'adresse dont l'élément le plus simple est un contact, doit permettre à l'utilisateur de :

    *Créer des contacts*
    *Lire un contact (liste, zone de recherche…)*
    *Mettre à jour un contact*
    *Supprimer un contact*

Si l'une ou l'autre de ces opérations fondamentales manque, le logiciel sera considéré comme incomplet.
 [masquer]
v · m
Bases de données
_Principe_ 	

    Clé Index ACID CRUD Transaction Partition Optimisation de requête.

_Modèle_ 	

    Structure de données Intégrité des données Langage de définition de données Langage de requête.

_Données_

    Champ Table Vue Procédure stockée Déclencheur.

_Composants_

    ODBC JDBC Dictionnaire des données.

_Opérations_

    Select Jointure Insert Update (SQL) Delete (SQL) Commit Rollback Merge Curseur.
