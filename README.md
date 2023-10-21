API Rest développé en Node JS relié à une base de donnée MongoDB.

Elle renvoie une liste de mots avec différents attributs qui sont : 

  - word : le mot en question
  - mask : un nombre d'underscore correspondant au nombre de lettres du mot
  - difficulty : sa difficulté
  - clue : Un indice sur le mot

Développer dans le but d'être utilisé dans le "jeu du pendu".

API publique donc accessible par qui bon le souhaite, voici les différentes routes de l'API.

https://words-api-v1.onrender.com/api/v1/words => Vous renvoie la liste entière des mots contenus dans ma base de données. C'est à dire, environ 1 000 mots.

https://words-api-v1.onrender.com/api/v1/words/easy-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté facile.

https://words-api-v1.onrender.com/api/v1/words/medium-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté moyen.

https://words-api-v1.onrender.com/api/v1/words/difficult-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté difficile.

https://words-api-v1.onrender.com/api/v1/words/easy-medium-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté facile et moyen.

https://words-api-v1.onrender.com/api/v1/words/easy-hard-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté facile et difficile.

https://words-api-v1.onrender.com/api/v1/words/medium-hard-words => Vous renvoie la liste de tous les mots ayant l'attribut de difficulté moyen et difficile.
