# Parcours S04
- Ton repo : [https://github.com/o-clock-wave/S04-parcours-ssiohan](https://github.com/o-clock-wave/S04-parcours-ssiohan)
- Correcteur : etienne

# Feedback du prof

Ce feedback correspond à la version de ton parcours pushée le jour du parcours. Si tu as fait des modifications depuis et que tu veux un retour dessus n'hésite pas à me demander.

## Test 1

### Enoncé

- Créer une classe nommée "Mario" dans le fichier exo1.php
- Ajouter une propriété "lives"
- Créer le constructeur de la classe
- Dans le constructeur de la classe, donner la valeur 3 à la propriété "lives"

### Attendus

- [x] Syntaxe PHP
- [x] Déclaration de la classe
- [x] Propriété publique
- [x] Assignation d'une valeur à la propriété

### Commentaires

- Tu donnes une valeur à ta propriété en la définissant ; c'est bien. On peut également le faire dans le constructeur - ce sera plus pratique après, si tu veux pouvoir donner une autre valeur à l'initialisation de ton objet plutôt que la valeur par défaut (ici, 3).
- Sinon nickel :thumbsup:

## Test 2

### Enoncé

- Reprendre le code de l'exo1
- Changer la visibilité de "lives" en privé
- Créer le Getter "getLives"

### Attendus

- [x] Syntaxe PHP
- [x] Déclaration de la classe
- [x] Propriété privée
- [x] Assignation d'une valeur à la propriété
- [x] Déclaration d'un getter
- [x] Utilisation de `$this` dans une méthode

### Commentaires

- Mêmes remarques que précédemment
- Sinon nickel :thumbsup:

## Test 3

### Enoncé

- Créer une méthode takeHit dans la classe Mario pour supprimer une vie
- Créer une méthode up dans la classe Mario pour ajouter une vie

### Attendus

- [x] Syntaxe PHP
- [x] Déclaration de la classe
- [x] Propriété privée
- [x] Assignation d'une valeur à la propriété
- [x] Déclaration d'un getter
- [x] Utilisation de `$this` dans une méthode
- [x] Déclaration de méthodes
- [x] Incrémentation et Decrémentation de la propriété

### Commentaires

- Mêmes remarques que précédemment
- Sinon nickel :thumbsup:

## Test 4

### Enoncé


- Renommer la classe Mario en Hero
- Ajouter la propriété name permettant de stocker le nom du héros
- Modifier le constructeur de la classe
- Définir un paramètre pour le "nom" du héro
- Affecter la valeur de ce paramètre à la propriété correspondante
- Créer la méthode hello dans la classe
- Créer la bonne chaîne de caractères en concaténant avec la propriété contenant le nom du héros
- Retourner la chaîne de caractères générée

### Attendus

- [x] Syntaxe PHP
- [x] Déclaration de la classe
- [x] Propriétés
- [x] Modification du constructeur avec un paramètre
- [x] Déclaration de méthodes
- [x] Concaténation de la propriété
- [x] Retour d'une valeur

### Commentaires

- Mêmes remarques que précédemment
- Le nom de chaque héros est donné en paramètre à l'instanciation (ex : `$mario = new Hero('Mario')`) donc on va vouloir le récupérer dans le constructeur et le stocker dans une propriété de notre objet.
- Sinon nickel :thumbsup:
Une petite propriété public pour le name aurait été bien.

## Test 5

### Enoncé

- Analyser le code des tests effectués
- Noter toutes les méthodes à créer

### Attendus

- [x] Propriété pour la couleur et son getter
- [ ] Propriété pour la taille et son getter
- [ ] Propriété pour l'étoile et son getter
- [ ] Méthode pour changer la propriété de la taille
- [ ] Méthodes pour changer la propriété de l'étoile
- [ ] Ajouts des conditions dans la méthode `takeHit` pour tenir compte des propriétés et les modifier

### Commentaires

- Ce bonus était particulièrement complexe puisque l'énoncé ne venait plus guider le code. Tu as listé les méthodes attendues, c'est déjà pas mal !
Dommage, c'était presque ça ! Ce qui t'as sûrement trompé c'est lorsque tu as passé isBig et hasStar en propriétés. Ce sont des getters, complétés par les setters eatMushroom, receiveStar et vanishStar. Quand tu en est là, tu as donc des getters/des setters mais ? Pas de propriétés. 
Ainsi tu pouvais mettre en propriétés Star et big, deux booléens qui te permette de savoir si Mario est sous champis ou sous étoiles. Avec ça tu pouvais modifier takeHit pour prendre en compte ces deux nouveaux facteurs. 

## Test 6

### Enoncé

- Répondre au questionnaire sur les base de données

### Attendus

- [x] Répondre au QCM

### Commentaires

- Top, la partie conception :clap:
- Top, la partie sur la structure des tables :clap:
Tu as deux erreurs sur la partie SQL, içi il faut faire très attention car SQL : 
- Tu peux interroger des champs même si ils satisfont pas ta requête dans ce cas elle retournera 0
- En revanche si dans ta requête la syntaxe d'un champ n'est pas la bonne : erreur.
Il faut être très pointilleux sur les requêtes BDD !

## Général

- [x] Présence de commentaires dans le code
- Qualité du code
  - [x] Indentation et lisibilité du code
  - [x] noms de variables précis
  - [x] noms de variables en anglais
  - [x] variables et fonctions en "camelCase"

### Pistes de révisions


### Commentaires

- Bon parcours, bravo :clap:
Super réalisation, dommage pour le bonus tu n'étais pas loin. N'hésite pas à le reprendre pour voir où tu as coincé ! 
En tous cas, très bon boulot ! :thumbsup: