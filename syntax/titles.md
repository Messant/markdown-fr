# Titres

Comme nous avons commencé à écrire un document de réduction, nous devons ajouter un titre et quelques sous-entêtes.

Markdown prend en charge deux styles d'en-têtes, Setext et atx.

Les en-têtes de type Setext sont "soulignés" en utilisant des signes d'égalité (pour les en-têtes de premier niveau) et des tirets (pour les en-têtes de deuxième niveau). Par exemple:

......
Il s'agit d'un H1
=============

C'est un H2
-------------
......

Tout le nombre de sous-titres = 's ou -'s fonctionnera.

Les en-têtes Atx-style utilisent 1-6 caractères de hachage au début de la ligne, correspondant aux niveaux d'en-tête 1-6. Par exemple:

......
# Il s'agit d'un H1

## Il s'agit d'un H2

###### Il s'agit d'un H6
......


En option, vous pouvez "fermer" des en-têtes style atx. C'est purement cosmétique - vous pouvez utiliser cela si vous pensez qu'il semble mieux. Les hachages de fermeture n'ont même pas besoin de correspondre au nombre de hachages utilisés pour ouvrir l'en-tête. (Le nombre de hachures d'ouverture détermine le niveau d'en-tête.):

......
# Il s'agit d'un H1 #

## Ceci est un H2 ##

### Il s'agit d'un H3 ######
......


---

Voici un quiz sur les titres de réduction.

Sélectionnez les en-têtes valides:
- [x] `# hello`
Salut

> Les en-têtes ont besoin d'espace entre les caractères de hachage et le texte.

Sélectionnez les en-têtes valides:
......
......
tester
########
......
- [X]
......
tester
=======
......

> Seulement '=' et '-' sont acceptés pour souligner un en-tête.

---

