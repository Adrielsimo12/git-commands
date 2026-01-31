# Commande git

Liste des commandes git

## git init

- Permet d'initialiser un repertoire

## git add

- Permet d'ajouter un fichier ou des modifications dans le stagging

## git commit -m

- Permet d'enregistrer une modification en local
- Le message est important (-am pour add)

## git push

- Permet de pousser les modifications en ligne

## git status

- Permet de vérifier le status du repertoire
- Permet de lister les modifications à traiter

## git log

- Permet de lister les modifications

## git branch

- Permet de créer une branche

## git checkout

- Permet de passer d'une branche à une autre
- Permet de se déplacer d'une branche à une autre
- Avec l'option -b checkout crée la branche si elle n'existe pas

## git pull

- Permet de récupérer les modifications distantes

## git rebase

- Permet de récupérer les modifications de la branche mère
- Les modifications de la branche mère sont placées en dessous des modifications de la branche courante
- Les modifications de la branche courante sont placées au dessus des modifications de la branche mère

## git merge

- Permet de récupérer les modifications de la branche fille
- Permet de fusionner le contenu de 2 branches
- l'ordre des commit n'est pas toujours sauvegaarder
- Pour conserver l'ordre des commit il faut utiliser l'option --no-ff

## git reset --hard id

- Permet de supprimer un commit
- Permet de revenir à un commit défini par son identifiant
- Attention à utiliser avec précaution

## git diff

- Permet de comparer 2 commits

## git log

- Permet de lister les modifications

## git branch

- Permet de creer une branche

## git checkout

- Permet de changer de branche
- Avec git checkout -b creer et ce déplace
