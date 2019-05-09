# Installation et configuration de Symfony

Pour créer une nouvelle application Symfony, assurez-vous d'abord que votre version de PHP soit en 7.1 ou plus.

#### Création d'un nouveau projet:

` composer create-project symfony/website-skeleton mon-projet `

#### Celui-ci vous créera un nouveau projet optimisé pour les applications Web et toute ses dépendances. Si vous vous utilisez Symfony pour des microservices ou API sans toute les dépendances, veuillez utilisez cette commande:

` composer create-project symfony/skeleton mon-projet `

#### Une fois le projet crée, vous devez lancer le serveur. Pour réaliser cetta tâche il faut utiliser la commande suivante:

` php -S 127.0.0.1:8000 -t public `

Le chiffre 8000 qu'on renseigne, c'est le port par défaut qu'utilise Symfony mais vous pouvez le modifier si vous êtes déjà sur le 8000.