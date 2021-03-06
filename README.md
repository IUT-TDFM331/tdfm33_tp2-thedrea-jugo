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
#### 2. Relancer les tests à nouveau.Qu'avez-vous remarqué ?

Le fait de mettre une methode en dehors de la classe (public class{}) provoque une erreur dans les tests.

#### 4. Demandez aux autres membres du groupe de récupérer les derniers changements ?  Que remarquez-vous ?

Nous remarquons que la même erreur est présente chez tous
les utilisateurs.

##B. Mise en place de l'intégration continue
#### 6. Allez sur votre repo Github. Que remarquez-vous ?

![img.png](img.png)

On remarque que le fait d'avoir ajouter le maven.yml permet de compiler automatiquement sur github lors d'un push ou
commit. De ce fait, github nous indique qu'il y a une erreur à ce niveau là car celui-ci compile à chaques fois.
#### 9. Lancez les tests. Que remarquez-vous ?

Le test décommenté provoque l'erreur suivante (renvoi false mais attend true):

![img_1.png](img_1.png)


#### 10.Commit + push avec le message 'Ajouter un mauvais test'. Que remarquez-vous ?

Lors du push au niveau du repo Github il n'y a pas d'erreur. On en déduit donc que les erreurs liées au tests ne sont 
pas pris en compte.

#### 13. Allez sur votre repo Github . Que remarquez-vous ?

La compilation des tests est maintenant prise en compte. Il y a donc l'erreur du test décommenté qui est affichée.

![img_2.png](img_2.png)

