# Parcours S06 et S07
- Ton repo : [https://github.com/o-clock-wave/S06-parcours-ssiohan](https://github.com/o-clock-wave/S06-parcours-ssiohan)
- Correcteur : fabio

# Feedback du prof

Dans cet exercice on a pu voir comment dialoguer avec un client en termes simples pour traduire ses besoins en documents techniques.

## Etape 1 : Création du dictionnaire de données

### Livrable

- Fichier Markdown ou PDF ou autre, du dictionnaire de données.

### Attendus

- [x] Présence du Dictionnaire de données
- [x] Présentation & pertinence générale
- [x] Types de données
- [x] Commentaires

### Commentaires

- Bien les commentaires.
- Bien pour cette étape !

## Etape 2 : Le schéma entité-association (MCD)

### Livrable

- Le schéma entité-association, MCD (au format image)

### Attendus

1. Base
- [x] Présence du schéma entité-association (MCD)
- [x] Entités : `Quizz`, `Question`, `Answer`, `Tag`, `Level`, `User`
- [x] `Level` + `Question`: OneToMany (1:n)
- [x] `Quizz` + `Question` : OneToMany (1:n)
- [x] Catégorisation de `Quizz` via ManyToMany avec `Tag`

2. On précise
- [x] Double relation entre les questions et les réponses : `Question` + `Answer`: OneToMany (1:n) et `Question` + `Answer`: OneToOne (1:1)


3. Bonus
- [x] Relation `User` + `Answer` : ManyToMany (n:m)

### Commentaires


- Attention à certaines de tes relations qui sont inversées : un thème peut être sur plusieurs quizs, mais un quiz n'a qu'un thème. De même pour auteur.
- On peut partir du principe qu'un auteur est un user, sans distinction.
- Bien vu pour la bonne réponse en booléen. On pouvait aussi faire deux relations entre Question et Answer pour stocker l'ID de la bonne réponse dans la question.
- Très bon MCD sinon ! 

## Etape 3 : La structure de la base de données physique (MLD)

### Livrable

- Le MLD et la structure de la base de données physique (sous forme d'un fichier sql).

### Attendus

- [x] Présence la structure de la base de données physique
- [x] Nommage (minuscules, snake_case, pas de suffixe entité)
- [x] Primary key simple  - entités
- [ ] Primary key composée - associations
- [x] Foreign Key

### Commentaires

- Bien les clefs primaires.
- Bien l'AUTO_INCREMENT sur les clefs primaires.
- Bien les clefs étrangères.
- Tu as des relations manyToMany dans ton MCD, il devrait en découler des tables de pivot entre les entités concernées.


## Etape 4 : Users stories

### Livrable

- Fichier Markdown ou PDF ou autre, des users stories.

### Attendus

- [x] Présence des users stories
- [x] Présentation & pertinence générale
- [ ] Respect de la demande du client

### Commentaires

- Pas mal ! Dans tes US, un utilisateur peur valider ses réponses, mais pas accéder au quiz ?

## Etape 5 : Routes

### Livrable

- Fichier Markdown ou PDF ou autre, des routes.

### Attendus

- [x] Présence des routes
- [x] Présentation & pertinence générale
- [x] Respect de la demande du client

### Commentaires

- Pour une formulaire du coup on aura une route en GET pour l'affichage + une route en POST pour le traitement
- Une route POST ne sert qu'à envoyer des informations pas en afficher.
- Il faut pouvoir soumettre tes réponses au quiz :wink:

## Etape 6 : Wireframe de la home [Bonus]

### Livrable

- Fichier JPG, PDF ou autre, du wireframe de la home.

### Attendus

- [x] Présence du wireframe (bonus)
- [x] Présentation & pertinence générale
- [x] Respect de la demande du client

### Commentaires

- Ton wireframe me semble correct, mais il n'est pas du tout légendé. Il faut légender au maximum pour lever toute ambiguïté. Par exemple, comment accéder à un quiz ? Je présume que c'est en cliquant sur le titre mais ça peut être aussi en cliquant sur tout le bloc?


## Général

- Qualité des éléments fournis
  - [x] Présences des documents demandés
  - [x] Structures Exports SQL

- Professionnalisme
  - [x] Respect du CDC
  - [x] Livraison dans les temps


### Pistes de révisions

- [BDD](https://github.com/O-clock-Alumni/fiches-recap/tree/master/bdd)
- [MCD - Modèle Entité-Association](https://github.com/O-clock-Alumni/fiches-recap/blob/master/bdd/conception-03-mcd.md)


### Commentaires

Très bon parcours ! Tu as rendu de très bons documents et même le bonus ! Pour t'améliorer essaye de mieux comprendre les relations et comment les traduire sur une vraie BDD.