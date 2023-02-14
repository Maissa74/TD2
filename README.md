# TD2
```
Question 1 : crée un fichier avec le contenu d'un epage WEB grace à curl
l https ://en.wikipedia.org/wiki/List_of_cyberattacks > cyberattacks.txt
```

```
Question 2: afficher seulement les phrases qui contiennent meta :
cat cyberattacks.txt | grep "meta"
```

```
Question 3: afficher seulement meta et le mot d'après 
grep -o -E "meta[[:alpha:]]+" cyberattacks.txt
```


