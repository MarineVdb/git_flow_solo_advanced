# Git - Gitflow solo advanced

Le but de cet exercice est de maîtriser une utilisation plus avancée de `git` avec les branches.

Cette méthode est adaptée pour la maintenance d'un projet en versions successives par un unique développeur.

## Étapes

D'abord :

- créez un nouveau dossier de projet (le nom du projet est libre)
- initialisez votre repo git
- créez un repo git distant sur github
- faites le lien entre votre repo local et le repo distant

Ensuite procédez aux étapes suivantes :

1. branche `master` : créez le fichier de documentation `README.md`
2. créez la branche `home`
3. branche `home` : créez le fichier html `index.html`
4. branche `home` : modifiez le fichier html `index.html`
5. branche `master` : fusionnez en local (pas sur github) la branche `home`
6. branche `master` : poussez la branche sur github
7. créez la branche `contact`
8. branche `contact` : créez le fichier html `contact.html`
9. branche `contact` : modifiez le fichier html
10. créez la branche `bugfix` en partant de la branche `master`
11. branche `bugfix` : modifiez le fichier html `index.html`
12. branche `master` : fusionnez en local (pas sur github) la branche `bugfix`
13. branche `master` : poussez la branche sur github
14. branche `contact` : rebasez votre branche sur la branche `master`
15. branche `contact` : modifiez le fichier html
16. branche `master` : fusionnez en local (pas sur github) la branche `contact`
17. branche `master` : poussez la branche sur github

## Livrables

Vous devez m'envoyer un fichier zip de votre projet et le lien github du projet.
Cela va me premettre de comparer l'historique du repo local et du repo distant sur github.