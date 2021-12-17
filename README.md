[![Open in Github](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://github.com/IUT-TDFM331/tdfm33_tp2-thedrea-jugo.git)

#  TD2 - Intégration continue
Dans ce rendu nous répondrons aux questions du TD2 du module
"M331 - Méthodologie de la production d'applications"

##2. Créer le projet
### Pourquoi les tests mettent autant de temps ?

La durée du tri est imapctée par la taille du tableau.
En effet, le tableau créé pour le test à une taille de 50 000 entiers.
Le test, tri à chaques fois un tableau de taille -1 donc 50000 puis 49999...

C'est donc cela qui prends du temps...

##3. Intégration continue
###A. S'assurer que le code de l'application ne comporte pas d'erreurs
#### Qu'avez-vous remarqué ?

Le fait de mettre une methode en dehors de la classe (public class{}) provoque une erreur dans les tests

#### Que remarquez-vous ?

Nous remarquons que la même erreur est présente chez tous
les utilisateurs.

##B. Mise en place de l'intégration continue
#### Que remarquez-vous ?
