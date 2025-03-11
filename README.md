# eval-final
éval final de la formation : 

Partie 1: Concepts de Base

Html : 

Pour Mon tire j'ai ajouter la balise "h1" qui représente le Titre principal de ma page 

Pour ajouter un paragraphe à ma page j'ai ajouter la balise "p" qui comme sont nom l'indique permet d'ajouter du text

Pour ajouter un lien on peut utilisé la balise "a" pour y coller son lien ou un lien externe

Pour ajouter une image à ma page j'ai ajouter la balise "img" qui permet comme sont nom l'indique d'ajouter une image qu'on peut soit importé depuis son ordinateur

pour mettre un bouton on utilise juste la balise "bouton"


Js : 

Le code JavaScript interagit avec le DOM(Document Object Model) en côté client pour manipuler la structure et le contenu d'une page web. Ce code est exécuté dans le navigateur de l'utilisateur, permettant ainsi de modifier les éléments du DOM en temps réel, sans nécessiter de rechargement de la page.

JavaScript peut identifier des éléments du DOM à l'aide de méthodes telles que "getElementById", "querySelector", et "querySelectorAll". Ces méthodes permettent de récupérer des éléments spécifiques ou des ensembles d'éléments basés sur leurs "id", "class", ou types de balises.

Partie 2: Projet Pratique
Projet : Création d'un Site Web de Blog Simple






Partie 3: Questions Théoriques
__________
HTML/CSS/JS

Différence entre Grid et Flex en CSS :

En CSS ;
Grid est un système bidimensionnel qui permet d'organiser les éléments à la fois en lignes et colonnes.
Alors que Flexbox est un système unidimensionnel qui aligne les éléments soit en ligne, soit en colonne.

Différence entre let, const et var en JavaScript :

var : Portée fonctionnelle, peut être redéclarée et réassignée.
let : Portée de bloc, ne peut pas être redéclarée mais peut être réassignée.
const : Portée de bloc, ne peut être ni redéclarée ni réassignée après affectation.

Programmation orientée objet en JavaScript (POO):

La POO en JavaScript repose sur des objets, qui sont des instances de classes contenant des propriétés et des méthodes.

__________
PHP

Connexion à une base de données MySQL en PHP
Pour se connecter à une base de données MySQL en PHP, on utilise PDO ou mysqli.

Expliquez comment vous connecteriez à une base de données MySQL en utilisant PHP :

$pdo = new PDO("mysql:host=localhost;dbname=ma_base", "utilisateur", "mot_de_passe");

Donnez un exemple de requête SQL pour récupérer des données d'une table :

Requête SQL pour récupérer des données d'une table par exemple ici la table "ballons"

SELECT * FROM ballons WHERE quantity = 20;

Cela récupère la quatité restant de ballon qui corespond ici à 20.

la table peut en elle contenir des colonnes ici on peut rajouté d'autre chose comme le marque ou la couleur :

SELECT marque, couleur FROM ballons WHERE quantity = 20;
