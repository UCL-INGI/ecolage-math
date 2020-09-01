*******
Théorie
*******

1. Implication
==============

Considérons plusieurs propositions relevant respectivement d’un contexte
géométrique, arithmétique et de la vie courante.

-  :math:`P_{1}` : Les diagonales du quadrilatère :math:`ABCD` se
   coupent en leur milieu.

-  :math:`Q_{1}` : Le quadrilatère :math:`ABCD` est un parallélogramme.

-  :math:`P_{2}` : :math:`n` est un naturel multiple de 4.

-  :math:`Q_{2}` : :math:`n` est un naturel multiple de 2.

-  :math:`P_{3}` : Il pleut.

-  :math:`Q_{3}` : Ma pelouse est arrosée.

Ces **propositions** sont susceptibles d’être vraies ou fausses. Mais au
regard de celles-ci, on constate que

.. math:: P_{1}\Rightarrow Q_{1}, \quad P_{2}\Rightarrow Q_{2}, \quad P_{3}\Rightarrow Q_{3}

Ce qui peut se lire de différentes façons:

-  :math:`P` implique :math:`Q`

-  Si la proposition :math:`P` est vraie, alors la proposition :math:`Q`
   est vraie (si :math:`P`, alors :math:`Q`)

-  La proposition :math:`P` est vraie seulement si la proposition
   :math:`Q` est vraie (:math:`P` seulement si :math:`Q`)

-  La proposition :math:`Q` est une condition nécessaire à la
   réalisation de la proposition :math:`P` (:math:`Q` est CN à
   :math:`P`)

Réciproque
----------

La réciproque de l’implication de est l’implication
:math:`Q\Rightarrow P`. Ce qu’on peut lire de différentes façons:

-  :math:`Q` implique :math:`P`

-  La proposition :math:`P`\ est vraie si la proposition :math:`Q` est
   vraie (:math:`P` si :math:`Q`)

-  La proposition :math:`Q` est une condition suffisante à la
   réalisation de la proposition :math:`P` (:math:`Q` est CS à
   :math:`P`)

Ce n’est pas parce qu’une implication est vraie que sa réciproque l’est
aussi. Dans les trois exemples considérés :

.. math:: Q_{1}\Rightarrow P_{1},\quad Q_{2}\nRightarrow P_{2}, \quad Q_{3}\nRightarrow P_{3}

Ce n’est pas parce que "ma pelouse est arrosée" que cela est du à la
pluie. L’arrosage peut être artificiel. Ce n’est pas parce qu’un nombre
(6 par exemple) est multiple de 2, qu’il est multiple de 4.

Contraposée
-----------

Si on note :math:`\neg P`, la négation de la proposition :math:`P`, la
contraposée de :math:`P\Rightarrow Q` est
:math:`\neg Q\Rightarrow \neg P`. On nie donc les affirmations :math:`P`
et :math:`Q` et on renverse le sens de l’implication. Si une implication
est vraie, la contraposée est vraie également, ce qui fait bien
comprendre le sens de la condition nécessaire. Par exemple, comme
":math:`n` est un naturel multiple de 4", implique que ":math:`n` est un
naturel multiple de 2"; si :math:`n` n’est pas multiple de 2, il n’est
certainement pas multiple de 4. Ou encore si "ma pelouse n’est pas
arrosée", c’est nécessairement "qu’il ne pleut pas".

Équivalence
-----------

Dans les cas où

.. math:: P\Rightarrow Q , \quad  Q\Rightarrow P

on parde **d’équivalence** et on note

.. math:: P\Leftrightarrow  Q

Ce qu’on peut lire de différentes façons:

-  Les propositions :math:`P` et :math:`Q` sont équivalentes

-  La proposition :math:`P`\ est vraie si et seulement si la proposition
   :math:`Q` est vraie (:math:`P` si et seulement si :math:`Q`)

-  La proposition :math:`Q` est une condition nécessaire et suffisante à
   la réalisation de la proposition :math:`P` (:math:`Q` est CNS à
   :math:`P`)

2. Démonstration
================

Démontrer consiste à déduire qu’une proposition appelée **thèse** est
vraie, en partant de propositions appelées **hypothèses** que l’on
suppose être vraies le temps de la démonstration. Pour démontrer, on
s’appuie également sur des propositions mathématiques qui sont vraies
parce qu’elles sont admises comme telles ou parce qu’elles ont été
démontrées auparavant. Les propositions admises sont des axiomes, celles
qui sont démontrées sont des théorèmes.

Soit à démontrer que :math:`P_{1}\Rightarrow Q_{1}`.

Hypothèses : :math:`ABCD` est un quadrilatère (sous-entendu plan) Les
diagonales :math:`[AC], [BD]` se coupent en leur milieu.

Thèse : :math:`ABCD` est un parallélogramme

La thèse se réfère à la définition de parallélogramme comme étant un
quadrilatère formé de deux paires de côtés parallèles. La démonstration
repose sur diverses propriétés comme un axiome, le premier cas
d’isométrie des triangles (Côté-Angle-Côté) et un théorème qui dit que
si deux droites coupent une troisième en formant des angles alternes
internes de même amplitude, alors elles sont parallèles.

Pour prouver une équivalence comme :math:`P\Leftrightarrow  Q`, on
démontre souvent les deux implications l’une après l’autre.

Comme nous l’avons déjà mentionné, :math:`P\Rightarrow Q` est la
Condition Nécessaire. Ce qui exprime que si :math:`Q` n’est pas vraie,
:math:`P` ne l’est pas non plus. Tandis que :math:`Q\Rightarrow P` est
la Condition Suffisante. Ce qui exprime que :math:`Q` vraie suffit à
rendre :math:`P` vraie.

Pièges
------

Par essence, la démonstration est déductive et les étapes se succèdent
en respectant les règles logiques, ce que certains appellent l’hygiène
du mathématicien.

Un premier piège pour le débutant consiste à utiliser la thèse dans la
démonstration. C’est-à-dire qu’on utilise le résultat pour le prouver.
Dans l’exemple du quadrilatère qui a des diagonales qui se coupent en
leur milieu, il n’est pas rare de voir un apprenti géomètre se servir
erronément du parallélisme de deux côtés pour en déduire que des angles
alternes internes ont même amplitude et que des côtés sont parallèles...

Un autre piège consiste à affirmer une chose et son contraire au sein de
la même démonstration. Le principe de non-contradiction est à la base de
toute théorie mathématique. Aristore l’aurait formulé sous la forme :
"il est impossible qu’une seule et même chose soit, et tout à la fois ne
soit pas, à une même autre chose, sous le même rapport".

Des négations particulières méritent notre attention. Pour prouver
qu’une propriété n’est pas vraie pour toutes les valeurs de :math:`x`,
il suffit de trouver une valeur de :math:`x` pour laquelle la propriété
n’est pas satisfaite. En mathématiques, cela se passe très différemment
de ce qu’on observe dans de nombreux domaines de la vie courante où il
faut de nombreux contre exemples pour faire tomber une vérité. Par
ailleurs, pour nier qu’une propriété qui est vraie pour une valeur de
:math:`x`, il suffit de prouver que pour toutes les valeurs de :math:`x`
la propriété n’est pas satisfaite.

Envisageons maintenant différents types de démonstration...

Directe
-------

Cela consiste à démontrer la proposition énoncée en partant directement
des hypothèses données pour en arriver à la thèse par une suite
d’implications logiques.

Pour prouver que :math:`P_{2} \Rightarrow Q_{2}`, sachant que
:math:`P_{2}` est l’hypothèse et que :math:`Q_{2}` est la thèse,
commençons par traduire l’hypothèse :

.. math:: \exists m\in \mathbb{N}:n=4m

Ce qui veut encore dire que

.. math:: \exists k\in \mathbb{N}:n=2.2.m=2k \quad \text{en prenant} \quad k=2m

Ce qui prouve la thèse, à savoir que :math:`n` est un multiple de 2.

Par l’absurde
-------------

Cela consiste à supposer le contraire de la proposition énoncée et de
montrer qu’on aboutit alors à une contradiction ou impossibilité.

Pour prouver que le nombre :math:`\sqrt{2}` est irrationnel, on suppose
que ce n’est pas le cas, c’est-à-dire qu’il peut s’exprimer sous forme
de fraction de naturels:

.. math:: \exists m,n \in \mathbb{N}_{0}:\sqrt{2}=\frac{m}{n}

Il en résulte que

.. math:: m^2=2n^2

Ce qui veut dire que :math:`m^2` est pair. Mais le carré d’un naturel
pair est pair et inversement. D’où il existe un naturel :math:`m'` tel
que :math:`2m'=m`, :math:`4m'^2=m^2` et l’égalité (1) devient

.. math:: 2m'^2=n^2

Il en résulte que :math:`n^2` est pair. Mais le carré d’un naturel pair
est pair et inversement. D’où il existe un naturel :math:`n'` tel que
:math:`2n'=n`, :math:`4n'^2=n^2` et l’égalité (2) devient

.. math:: m'^2=2n'^2

Et ainsi de suite... Indéfiniment. Ce qui n’est pas possible puisque
:math:`n` et :math:`m` sont naturels et limités, on ne peut pas les
diviser indéfiniment par 2. Il faut donc rejeter l’hypothèse faite à
savoir que :math:`\sqrt{2}` puisse être rationnel.

Par contraposée
---------------

Démontrer que :math:`P\Rightarrow Q`, c’est équivalent à démontrer que
:math:`\neg Q\Rightarrow \neg P`.

Pour démontrer que "Si le dernier chiffre d’un nombre naturel :math:`n`
est 2 alors :math:`n` n’est pas le carré d’un entier", on peut démontrer
que si :math:`n` est le carré d’un naturel alors son dernier chiffre
n’est pas 2. En effet, si :math:`\sqrt{n}` se termine

-  par 1 ou 9, son carré se termine par 1.

-  par 2 ou 8, son carré se termine par 4.

-  par 3 ou 7, son carré se termine par 9.

-  par 2 ou 8, son carré se termine par 4.

-  par 4 ou 6, son carré se termine par 6.

-  par 5, son carré se termine par 5.

-  par 0, son carré se termine par 0.

Et jamais un carré ne se termine par 2.

Par récurrence
--------------

Pour prouver qu’une propriété :math:`P(n)` est vraie
:math:`\forall n \in \mathbb{N}`, on démontre qu’elle est vraie pour
:math:`n=0` et que si elle est vraie pour :math:`n`, cela implique
qu’elle est vraie pour :math:`n+1`.

Soit à démontrer par exemple que la somme des carrés des :math:`n`
premiers naturels est égale à :math:`\frac{n(n+1)(2n+1)}{6}`,
c’est-à-dire que

.. math:: 0+1+4+...+n^2=\frac{n(n+1)(2n+1)}{6}

Pour :math:`n=0`, la propriété est vraie car

.. math:: 0=\frac{0(0+1)(0n+1)}{6}

Si la propriété est vraie pour :math:`n`, alors

.. math:: 0+1+4+...+n^2+(n+1)^2=(0+1+4+...+n^2)+(n+1)^2=\frac{n(n+1)(2n+1)}{6}+(n+1)^2

Si on réduit au même dénominateur les deux termes du dernier membre de
l’égalité, puis qu’on met :math:`(n+1)` en évidence, on obtient

.. math:: 0+1+4+...+n^2+(n+1)^2=\frac{(n+1)[n(2n+1)+6(n+1)]}{6}=\frac{(n+1)[2n^2+7n+6]}{6}

On peut factoriser :math:`2n^2+7n+6=(n+2)(2n+3)` et finalement obtenir

.. math:: 0+1+4+...+n^2+(n+1)^2=\frac{(n+1)(n+2)(2n+3)}{6}=\frac{(n+1)(n+2)(2(n+1)+1)}{6}

Ce qui prouve que l’égalité est vraie pour :math:`n+1`.


