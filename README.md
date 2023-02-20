# TD2_1_linux_Grep: 

#Ex1

```
Question 1 :
ls -l

```

```
Q2:
ls -l | grep bin

```


```
Q3:
ls -l / | grep bin | awk '{print $5}'
```


```
Q4:
ls -l / | grep bin | awk '{print $6 $7 $8}'
```

```
Q5: 
ls -l / | grep bin | awk '{print $6 "-"  $7 "-"  $8}'
```





#Exo 2 

```
Question 1 : crée un fichier avec le contenu d'un epage WEB grace à curl
curl https://en.wikipedia.org/wiki/List_of_cyberattacks > cyberattacks.txt
```

```
Question 2: afficher seulement les phrases qui contiennent meta :
cat cyberattacks.txt | grep "meta"
```

```
Question 3: afficher seulement meta et le mot d'après 
grep -o -E "meta [[:alpha:]]+" cyberattacks.txt
```
```
Q4:
grep -o -E "meta [[:alpha:]]+" cyberattacks.txt | awk '{print$2}'
```

```
Q5:


```


















