# Projet python (tout le projet doit etre mis dans le dossier French d'Unitex GramLab)

## app.py
`app.py` lance le serveur en localhost port a definire la commande est :
```bash
    $ app.py <port>
```
## scraper.py 
  `scraper.py` va scrapper depuis le kda menna mlhih vidal : 
```bash
$ scraper.py <port> A-C
``` 
le resultat et tous les mots du vidal commencant par la lettre choisie
Génère la première version de susbt.dic

## enrichir.py 
Permet d'enrechir le subst.dic à partir de corpus-med (ajoute les medicaments qui ne se trouvent pas dans Vidal) .
Il génère: subst.dic (version enrichie), subt_enri.dic (contient que les medicaments extraits de corpus-med.txt) et infos2.txt ( informations sur le nombre de medicaments trouvés).

## unitex.py 
 script qui appelle unitex. 
Pour pouvoir unitliser UnitexToolLogger, il faut copier Unitex-GramLab\App>UnitexToolLogger.exe dans Unitex-GramLab\French>
OU BIEN : 
placer les trois scripts python (aspirer.py, enrichir.py et unitex.py) dans C:\................\Unitex-GramLab\App>
(là où se trouve UnitexToolLogger.exe)

## posologie.grf 
 graphe unitex qui extrait les posologiesde de traitement à partir du fichier texte corpus-medical.


RESULTATS OBTENUS:


