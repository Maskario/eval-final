# eval-final
éval final de la formation : 

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
