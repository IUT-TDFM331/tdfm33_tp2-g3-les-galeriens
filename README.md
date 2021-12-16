[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6564721&assignment_repo_type=AssignmentRepo)
## Contributors
G3
- Pasquier
- Cumont
- Brunetti
- Magaud

## Reponse 2.B Pourquoi les tests mettent autant de temps ?
Les tests prennent environ 17 secondes.
On peut dire que le temps est du au nombres de tests à faire en effet il va parcourir des liste conséquentes : 
IsWellSortedLargeArrays est celui qui prend le plus du temps car elle porte sur une liste de 50 000 valeurs.

## Reponse 3.A.2 Relancer les tests à nouveau.Qu'avez-vous remarqué ?
Nous pouvons remarquer que les testes ne fonctionnent pas en effet la methode que nous avons rajouté
se trouve en dehors de la classe SortAlgorithms.

## Reponse 3.A.4  Demandez aux autres membres du groupe de récupérer les derniers changements ? Que remarquez-vous ? 
Nous pouvons remarquer que les autres membres pouvons tout de même récuperer les erreurs. 

## Reponse 3.A.9  Lancez les tests Que remarquez-vous ? 
Quand on lance les tests en enlevant les commentaires dans le fichier SortAlgorithmsTest nous obtenons des erreurs tels que:
```
INFO: Method [badTest] took 0 ms.

org.opentest4j.AssertionFailedError: 
Expected :true
Actual   :false
```