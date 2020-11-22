<!-- effect=stars -->
# Que faire avec present !

Present est une petite application écrite en Python
qui permet de réaliser instantanément des présentations
à partir de vos fichiers Markdown en ligne de commande.

[vinayak-mehta/present](https://github.com/vinayak-mehta/present)

---
<!-- fg=white bg=black -->
## Pour identifier vos slides

Chaque bloque de texte, de votre fichier Markdow,
que vous souhaitez présenter dans un slide, doit
être séparé par ---

---
<!-- fg=black bg=white -->
## Comment utiliser present en lecture ?

Allez dans le répertoire qui contient le fichier
Markdown que vous souhaitez présenter et tapper :

```bash
present monfichier.md
```

Les contrôles se font avec le clavier :

- Quitter : q
- Slide précédent : b, flèche gauche, page précédente
- Slide suivant : n, barre d'espace, flèche droite, page suivante

---
<!-- fg=black bg=white -->
## Présenter du texte formatté

Mes idées sur ce sujet sont :

> Ma première idée,
> 
> Ma deuxième idée,
> 
> Ma troisièle idée.

Vous pouvez aussi utiliser le formatage Markdown habituel :

C'est du texte normal

C'est du **texte en gras**

C'est du `inline code`

* C'est une puce de texte

C'est un [lien](www.google.com)

---
<!-- fg=white bg=black -->
## Présenter des images

```
![MonImage](images/Apple1.png)
```

Et oui c'est du bon vieux 8 bites !

![MonImage](images/Pomme.png)

---
<!-- fg=black bg=white -->
## Présenter du code statique

Exemples de mon fantastique code :

```python
import os

print(os.getcwd())
```

```python
import shutil

columns, rows = shutil.get_terminal_size()
```

---
<!-- fg=black bg=white -->
## Présenter du code dynamique

Appuyez sur la touche r pour rejouer la séquence de code !

![codio](codio.yml)

---
<!-- effect=matrix -->
# Et quoi d'autre ?

---
<!-- fg=white bg=red -->
## Changer la couleur de vos slides

Vous pouvez changer la couleur de vos slides en jouant sur les deux options fg et bg.

Juste ajouter cette ligne dans votre fichier Markdown au début de votre slide.

```html
<!-- fg=white bg=red -->
```

Les couleurs possibles : black, red, green, yellow, blue, magenta, cyan, white

---
<!-- fg=white bg=black -->
## Enfin vous pouvez ajouter des effets

Juste ajouter cette ligne dans votre fichier Markdown au début de votre slide.

```html
<!-- effect=fireworks -->
```

Effets possibles : fireworks, explosions, matrix, plasma, stars

---
<!-- effect=fireworks -->
# Effet Fireworks
---
<!-- effect=explosions -->
# Effet Explosions
---
<!-- effect=matrix -->
# Effet Matrix
---
<!-- effect=stars -->
# Effet Stars
---
<!-- effect=plasma -->
# Effet Plasma