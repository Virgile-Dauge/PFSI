## PFSI : TP Assembleur
### TPs 9, 10, 11 : Sujets et corrections.
Pour assembler un fichier source (.src) il suffit de lancer la commande suivante :
```java -jar path_to_/microPIUPK.jar -ass path_to_/myProg.src```

L'archive java générera un fichier exécutable, mais toutefois lisible sous la forme `myProg.iup`.

Par la suite, il faut lancer le simulateur avec la commande suivante :
```java -jar path_to_/microPIUPK.jar -sim```

Puis charger le fichier iup précédemment généré afin d'en simuler l'exécution.

Pensez à cocher la case "Execution pas à pas".

Chaque clic sur le bouton d'exécution effectuera une nouvelle instruction.

### Crédits
TP 9 : Sylvain Cecchetto.
TP 10 : Théo Biasutto-Lervat.
TP 11 : Virgile Daugé
