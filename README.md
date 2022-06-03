

# MarkDown

Le MarkDown est un langage de balisage plus facile à lire que le html. Un fichier MarkDown est enregistré avec l'extension `.md`.
On peut utiliser Visual Studio Code pour coder en markdown. Utiliser le raccourci `CTRL + Shift + V` pour prévisualiser en direct le résultat sur Visual Studio Code.



## Les titres

# Titre un   
## Titre deux   
### Titre trois  
#### Titre quatre 
##### Titre cinq 
###### Titre six

On ajoute le symbole `#` pour ajouter des titres. Il y a 6 niveaux de titres. 

```
# Titre un   
## Titre deux   
### Titre trois  
#### Titre quatre 
##### Titre cinq 
###### Titre six 
```



## Saut de ligne

Pour insérer un saut de ligne, ajouter une ligne vide.
 

## Le format

Mot en italique : _mot_ 
Mot en gras : **mot**
Mot en gras et en italique : **_mot_** 
Mot barré :  ~~mot~~
Mot surligné :  ==mot==. 
Mot en indice : ~mot~
Mot en exposé : ^mot^ 

```
Mot en italique : _mot_ 
Mot en gras : **mot**
Mot en gras et en italique : **_mot_** 
Mot barré :  ~~mot~~
Mot surligné :  ==mot==
Mot en exposé : ^mot^  
```

## Citation
Citation de Descartes : 

> Je pense donc je suis.  
> 
>> Une autre citation incrustée 

```
Citation de Descartes : 

> Je pense donc je suis.
> 
>> Une autre citation incrustée 
```

## Lien internet 

[Ceci est un lien internet](www.google.com)
```
[Ceci est un lien internet](www.google.com)
```

## Liste non ordonnée
* item
* item
  * item
  * item
* item

```
* item
* item
  * item
  * item
* item
```

## Liste ordonnée
1. Item
2. Item
    1. Item
    2. Item
3. Item

```
1. Item
2. Item
    1. Item
    2. Item
3. Item
```

## Liste à coches

- [x] Je suis coché
- [ ] Je ne suis pas coché 
- [ ] Moi non plus 

```
- [x] Je suis coché
- [ ] Je ne suis pas coché 
- [ ] Moi non plus 

```




## Image

![titre de l'image](image.jpg)  

```![titre de l'image](image.jpg) ```
 

L'image doit être dans le même dossier que le fichier en markdown et doit être nommé image.jpg pour s'afficher. Sinon on a ceci : 

![titre de l'image](image_unkown.jpg)  
```![titre de l'image](image_unkown.jpg)```


## Code  

`` Pour écrire un mot en code, l'encadrer par le symbole ` ``
`` Pour écrire un bloc de code, l'encadrer par : ''' ``

## Tables

Il suffit d'ajouter `|` pour séparer verticallement les cellules et plusieurs tirets `-` pour séparer horizontalement les cellules.

| En-tête 1          | En-tête 2 |
| --------           | --------- |
| Ligne 1, colonne 1 | Ligne 1, colonne 2 | 
| Ligne 2, colonne 1 | Ligne 2, colonne 2 | 
| Ligne 3, colonne 1 | Ligne 3, colonne 2 | 

```
| En-tête 1          | En-tête 2 |
| --------           | --------- |
| Ligne 1, colonne 1 | Ligne 1, colonne 2 | 
| Ligne 2, colonne 1 | Ligne 2, colonne 2 | 
| Ligne 3, colonne 1 | Ligne 3, colonne 2 | 

```

On peut modifier l'alignement du texte de chaque colonne en utilisant les deux points `:`

| Aligner à gauche | Centrer | Aligner à droite |
| :--------------- | :-----: | ---------------: |
| Pommes           |  Rouge  |             5000 |
| Bananes          |  Jaune  |               75 |


```
| Aligner à gauche | Centrer | Aligner à droite |
| :--------------- | :-----: | ---------------: |
| Pommes           |  Rouge  |             5000 |
| Bananes          |  Jaune  |               75 |
```


## Ligne 

Pour ajouter une ligne, ajouter `---` entre deux lignes vides.

---

## Notes de bas de page 

Si on se trompe dans l'ordre de numérotation, la visualisation du markdown le corrige automatiquement. 


Ajouter des notes de bas de pages. [^1]
Une autre note. [^2]

[^1]: Ceci est une note de bas de page. 
[^2]: Autre note

```
Ajouter des notes de bas de pages. [^1]

[^1]: Ceci est une note de bas de page. 
[^2]: Autre note
```

## Emoji 


 :joy:   
 `:joy: `

:wink:
`:wink: `

:cry:
`:cry:`

## HTML   

On peut ajouter du html dans du Markdown

<ul> 
<li>liste 1</li>
<li>liste 2</li>
<ul> 


```
<ul> 
<li>liste 1</li>
<li>liste 2</li>
<ul> 
```
    
<img src="image.jpg" width="200"/>
``` <img src="image.jpg" width="200"/> ```