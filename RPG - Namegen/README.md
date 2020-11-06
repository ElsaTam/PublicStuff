# Générateur de noms

Basé sur le travail de Paul S. : [namegen for roll20](https://github.com/Roll20/roll20-api-scripts/tree/master/namegen)

## Utilisation dans Roll20

Il faut un comte professionnel pour utiliser ce script dans Roll20.

Copiez-collez le contenu du fichier [namegen.js](https://github.com/ElsaTam/PublicStuff/blob/master/namegen.js?raw=true) dans un nouveau script sur votre partie.

En jeu, vous pouvez préparer des macro spécifiques à votre partie :
- `!namegen english girl` pour générer un nom anglais de fille
- `!namegen english boy` pour générer un nom anglais de garçons
- `!namegen ?{Language|african|arabic|asian|french|english|germanic|hindi|italian|medieval|sanskrit|thai} ?{Gender|boy|girl}` pour une macro complète présentant tous les choix possibles

Le nom généré est envoyé en privé au MJ :

![ ](https://github.com/ElsaTam/PublicStuff/blob/master/Roll20_boy_english.png?raw=true)

## Utilisation dans le navigateur

Si vous n'avez pas de compte Roll20 pro, téléchargez le fichier [`namegen.html`](https://github.com/ElsaTam/PublicStuff/blob/master/namegen.html?raw=true) et lancez-le dans votre navigateur.

![ ](https://github.com/ElsaTam/PublicStuff/blob/master/html_screenshot.png?raw=true)

## Bases de données

Les fichiers `.csv` sont ceux utilisés pour générer des noms au hasard.

Le fichier `csvToArray.html` permet de transformer un tel fichier (en une colonne) en un tableau à utiliser dans le script javascript.