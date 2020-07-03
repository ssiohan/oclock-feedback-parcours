# Parcours S02

- Ton repo : [https://github.com/O-clock-Wave/S02-parcours-PHP-ssiohan](https://github.com/O-clock-Wave/S02-parcours-PHP-ssiohan)
- Correcteur : gsylvestre

# Feedback du prof

## Test 1

### Enoncé

- La fonction _calculPlage_ doit pouvoir recevoir 3 informations : prix du maillot, prix des lunettes, prix de la crème
- On doit retourner la somme des articles : 1 * maillot + 1 * paire de lunettes + 2 * crème solaire

### Attendus

- [x] Syntaxe PHP
- [x] Présence des 3 paramètres
- [x] Calcul de la somme
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:

## Test 2

### Enoncé

- Un nombre entre 1 et 49 doit être choisit aléatoirement
- Se servir de mt_rand capable de prendre 2 bornes (minimum, maximum)

### Attendus

- [x] Syntaxe PHP
- [x] Utilisation de la fonction `mt_rand` ou `rand`
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:

## Test 3

### Enoncé

- Dans la fonction, définir un tableau pour stocker les différents tirages, tableau qui sera retourné en fin de fonction
- POUR les 5 premiers numéros, stocker dans ce tableau un tirage aléatoire entre 1 et 49
- Une fois ces 5 numéros obtenus, ajouter au tableau un nombre tiré aléatoirement entre 1 et 10

### Attendus

- [x] Définition d'un tableau
- [ ] Utilisation d'une boucle pour répéter une action
- [ ] Ajout d'un élément dans un tableau
- [x] Retour d'une valeur

### Commentaires

- Tu as définis ton tableau avec les valeurs directement à l'intérieur. C'est déjà bien mais on peut utiliser une boucle pour répéter une action. Cela nous permet de renseigner les valeurs en dur 1 et 49 à un seul endroit.
- Sinon RAS :ok_hand: !

## Test 4

### Enoncé

- La fonction numerosLoto() de l'exo précédent permet déjà de générer les numéros de loto pour une grille
- On va réutiliser cette fonction pour chaque grille demandée => on copie-coller la fonction ici (include impossible)
- Pour générer X grilles, on a besoin de savoir combien de grilles l'utilisateur veut générer => paramètre de la fonction
- Après avoir initialiser le tableau contenant, à terme, toutes les grilles
- On va créer une boucle s'exécutant autant de fois qu'il y a de grilles à remplir
- A chaque itération de la boucle, on ajoute dans notre tableau, le tableau retourné par la fonction numerosLoto()
- A la fin, il ne nous reste plus qu'à retourner notre tableau de grilles
BONUS
- le paramètre donnant le nombre de grilles est optionnel
- et sa valeur par défaut est 2

### Attendus

- [x] Définition d'un paramètre
- [x] Définition d'un tableau
- [x] Utilisation d'une boucle pour répéter une action
- [x] Appel d'une fonction
- [x] Ajout d'un élément dans un tableau
- [x] Retour d'une valeur
- [x] Bonus : Paramètre optionnel

### Commentaires

* wooohooo superbe.

## Test 5

### Enoncé

- Récupérer dans l'url, en GET, l'info name
- Structurer une phrase de salutation avec l'info récupérée

### Attendus

- [x] Utilisation de `$_GET` pour récupérer un paramètre en URL
- [x] Concaténation d'une variable dans une chaîne de caractère
- [x] Retour d'une valeur

### Commentaires

- RAS :ok_hand: !

## Test 6

### Enoncé

- indenter correctement et manuellement le code
  - avec les "Parse error", l'extension Beautify ne sait pas correctement indenter
- lire et interpréter chaque erreur affichée par PHP
- PHP nous indique toujours le fichier et la ligne de code qui a généré l'erreur
  - exception : pour l'erreur Unexpected xxx l'erreur se situe avant la ligne indiquée
- une fois les "Parse error" résolues, il faut rendre le programme fonctionnel

### Attendus

- [x] Interprétation des erreurs
- [x] Indentation propre
- [ ] Programme fonctionnel

### Commentaires

* wahhh presque ! Bien joué ;)

## Général

- [ ] Présence de commentaires dans le code
- Qualité du code
  - [x] indentation et lisibilité du code
  - [x] noms de variables précis
  - [ ] noms de variables en anglais
  - [x] variables et fonctions en "camelCase"

### Pistes de révisions


### Commentaires

Excellent parcours, bravo :clap: