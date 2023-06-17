# Cahier des charges pour le challenge "Mini-Faussaire"

## I. Objectif
Le projet vise à développer une application web monopage capable de générer des données de test réalistes pour diverses utilisations, avec la possibilité d'exporter ces données dans plusieurs formats (SQL, CSV, JSON).

## II. Fonctionnalités clés

### 1. Génération de données

L'utilisateur doit pouvoir générer les types de données suivants :
- Nom
- Prénom
- Téléphone
- Email
- Adresse
- Code postal/Zipcode
- Ville
- Région/Province/État
- Pays
- Textes
- Valeurs numériques
- Coordonnées géographiques
- Couleur
- Mot de passe
- GUID
- Valeurs binaires, octales, hexadécimales

Les champs tels que le nom, le prénom, le téléphone, l'email, l'adresse, le code postal, la ville, la région et le pays doivent être générés à partir de données réalistes ou plausibles. Les données doivent être capables d'être formatées pour correspondre aux formats français, anglais et allemand.

### 2. Exportation de données

L'utilisateur doit avoir la possibilité d'exporter les données générées dans les formats suivants :
- SQL
- CSV
- JSON

### 3. Interface utilisateur

L'application sera une application web monopage, facile à utiliser, avec une interface intuitive. L'utilisateur pourra sélectionner les types de données qu'il souhaite générer à partir d'une liste de cases à cocher, indiquer le nombre de données à générer, et sélectionner le format d'exportation.

## III. Architecture et technologies

Le site web sera construit autour d'une base de données MariaDB. L'architecture devra suivre les meilleures pratiques en matière de sécurité, de performance et de maintenabilité.

Les technologies envisagées pour le développement sont les suivantes :
- La technologie utilisée pour le frontend est libre.
- La technologie utilisée pour le backend est libre.
- MariaDB pour la base de données.

## IV. Livrables

- Documentation technique et utilisateur
- Code source complet avec commentaires
- Tests unitaires et d'intégration
- Site web déployé et opérationnel

## V. Contraintes

Le projet doit être terminé et livré dans un délai de 3 mois à partir de la date de début du projet. Le budget alloué pour le projet est nul (c'est juste un projet perso pour porto-folio). Toutes les technologies utilisées doivent de préférence être open source.

## VI. Critères de réussite

La réussite du projet sera mesurée par les critères suivants :
- Respect du délai et du budget( :p )
- Originalité du projet, le clonage d'une solution existante n'est pas une option
- Le générateur de données produit des données réalistes et variées
- Les données peuvent être exportées correctement dans les trois formats
- Le site web est facile à utiliser et ne présente pas de bugs significatifs
- Le code est bien organisé, bien commenté et suit les conventions de codage
- Le projet comprend des tests unitaires et d'intégration pour assurer la qualité du code

