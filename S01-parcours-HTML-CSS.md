# Parcours S01

- Ton repo : [https://github.com/O-clock-Wave/S01-parcours-HTML-CSS-ssiohan](https://github.com/O-clock-Wave/S01-parcours-HTML-CSS-ssiohan)
- Correcteur : yann

# Feedback du prof

Tu as demandé un retour plus personnalisé sur ton travail, ou on a eu l'occasion de t'en faire un. Les explications ci-dessous visent à compléter l'auto-correction que tu as reçu, en analysant ce que tu as fait, toi. Si elles ne correspondent pas suffisamment à tes interrogations, ou si certains passages ne te semblent pas clairs, n'hésite pas à revenir vers nous pour que l'on précise cela ensemble.

## Test 1

### Enoncé

- Mettre les 2 paragraphes l'un à côté de l'autre
- Gérer l'espace entre les 2 paragraphes
- Mettre en gras la balise `strong`
- Mettre en italique la balise `em`
- Mettre un espace au-dessus et en-dessous de chaque paragraphe

### Attendus

- [x] Syntaxe CSS
- [x] Ciblage CSS
- [x] Mettre les 2 `<div>` enfants de l'id `aToiDeJouer` côté à côté, en utilisant **Flex**, sinon **float**
- [ ] Gérer l'espace entre les 2 `<div>` avec un `justify-content: space-between;` ou des `margin`
- [x] Gras avec la propriété `font-weight` et la valeur `bold` ou `700` ou +
- [x] Italique avec la propriété `font-style`
- [x] Espace vertical entre chaque paragraphe grâce à `margin`, sinon `padding`

### Commentaires

- Sinon, comme tu as utilisé `flex`, tu peux aussi regarder du côté de `justify-content: space-between;` pour gérer l'espacement horizontal entre tes blocs de texte.
- Sinon nickel :thumbsup:

## Test 2

### Enoncé

  - Donner une dimension équivalente à 32px aux div
  - Arrondir les div pour faire des ronds plutôt que des carrés
  - Positionner les ronds côte-à-côte
  - Mettre un fond gris sur les ronds
  - Au hover, chaque rond a une couleur différente (prise depuis le logo Google)
  - Bonus: animation grossissante au survol

### Attendus

- [x] Syntaxe CSS
- [x] Ciblage CSS
- [x] Dimensions de `2rem` sur les `.loading_circle`
- [x] Arrondis grâce à `border-radius` sur les cercles
- [x] Cercles disposés côte-à-côte grâce à `flex` ou `float`
- [x] Cibler le survol grâce à la pseudo-classe `:hover`
- [x] Définir chaque couleur de fond individuellement
- [x] Bonus : `transition` d'une seconde
- [x] Bonus : `transform:scale`

### Commentaires

- Bon bah nickel ; avec ces super bonus, tu vas pouvoir postuler chez Google :heart_eyes:

## Test 3

### Enoncé

- HTML
  - Créer un élément pour le carré de 100px
  - Créer un élément pour le rond rouge
- CSS
  - Positionner le carré noir autre centre (vertical et horizontal) de la fenêtre, même si on scroll
  - Rendre rond un élément HTML à la base carré ou rectangulaire
  - Positionner ce rond en haut à droite du carré noir, même si on scroll

### Attendus

- [x] Ajout de balises `<div>` ou autre, avec attribut `id` ou `class` pour les cibler en CSS
- [x] Syntaxe CSS
- [x] Ciblage CSS
- [x] Affecter les bonnes couleurs de fonds aux 2 éléments
- [x] Définir la hauteur et la largeur des 2 éléments avec `width` et `height`
- [ ] Fixer le carré noir à la fenêtre (et non la page) avec `position:fixed;`
- [x] Placer le carré noir au centre de la fenêtre en jouant sur les propriétés `top`,  `left` et `margin`
- [x] Rendre l'élément rouge rond grâce à la propriété `border-radius`
- [x] Fixer le rond rouge en haut à droite du carré noir avec `position: absolute;` + `top` & `right` (ou `left`)

### Commentaires

- C'est déjà bien d'avoir fixé le carré noir à la page, mais il fallait le fixer à la fenêtre => il ne bouge pas, même si on scroll
- Sinon RAS :ok_hand: !

## Test 4

### Enoncé

- CSS
  - Positionner 2 blocs par ligne
  - Chaque bloc doit occuper 50% de l'espace (en hauteur comme en largeur)
  - Centrer le contenu de chaque bloc

### Attendus

- [x] Syntaxe CSS
- [x] Ciblage CSS
- [x] Mettre le container en flex
- [x] Activer flex-wrap sur le container
- [x] Affecter les bonnes couleurs de fonds aux 2 éléments
- [x] Définir la hauteur et la largeur des éléments avec `width` et `height`
- [x] Parties blanches en flex, avec alignements verticaux et horizontaux centrés

### Commentaires

- Nickel ce drapeau du Panama ! Allez, tu nous fait la Grèce, maintenant ? :sunglasses:

## Test 5 - BONUS

### Enoncé

- Créer un losange à partir d'un carré
  - Tourner le carré de 45°
  - Tourner l'image de -45°
  - Définir la taille de l'élément
  - Cacher ce qui pourrait déborder de l'élément
- Mettre un effet d'ombre tout autour du losange

### Attendus

- [x] `margin-left:auto;` & `margin-right:auto;` pour centrer la `<div>`
- [x] Tourner la `<div>` de 45° avec `transform:rotate(45deg);`
- [x] Définir la hauteur et la largeur de la `<div>` avec `width` et `height`
- [x] Tourner l'image dans l'autre sens de 45° avec `transform:rotate(-45deg);` pour la remettre "droite"
- [x] Couper les bouts d'image qui débordent de la `<div>` avec `overflow:hidden;`
- [x] Décaler l'image pour qu'elle rentre dans le losange avec des `margins` positives ou négatives
- [x] Mettre un effet d'ombre avec la propriété `box-shadow`

### Commentaires

- Ce bonus est très difficile et tu l'as parfaitement réalisé, félicitations :muscle: !

## Test 6 - BONUS

### Enoncé

Styliser le table comme l'image fournie
- Mettre un background en dégradé sur les liens "Order Now"
- Gérer les bordures des cellules
- Gérer les espaces des cellules
- Cibler les cellules par "zone"
- Alterner la couleur de fond de chaque ligne
- Gérer les 2 polices

### Attendus

- [ ] Background dégradé avec `background-image: linear-gradient(xxxx);`
- [ ] Alterner le background avec une couleur de fond par défaut, et une autre pour la classe `odd` sur le `<tr>`
- [ ] Définir un background différent pour la première colonne en ciblant `.column1`
- [ ] Bordure sur `<table>`, `<th>` et `<td>` + `border-collapse: collapse;` sur `<table>` pour que les bordures "fusionnent"
- [ ] `padding`, `height` sur les cellules ou `line-height` sur les textes
- [ ] Cibler les balises `<th>` différentes dans `<thead>` et `<tfoot>`
- [ ] `font-family: "Trebuchet MS", Arial, sans-serif;` pour `#aToiDeJouer thead th` et `#aToiDeJouer tfoot th strong`
- [ ] Centrer les textes avec `text-align` (sauf colonne de gauche)

### Commentaires

- Et oui, un BONUS, ~c'est difficile~ c'est long

## Général

- [ ] Présence de commentaires dans le code
- [x] Précision des ciblages/selectors
- [ ] Utilisation de préfixes (compatibilité avec anciens navigateurs)
- Qualité du code
  - [x] indentation et lisibilité du code

### Commentaires

- Excellent parcours, bravo :clap: