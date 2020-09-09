****************
Théorie
****************

Les fonctions exponentielles et logarithmes
============================================

Définition
-----------

Soit :math:`a` un nombre :math:`\in \mathbb{R}_O^+ \backslash\{1\}` .

**L'exponentielle de base** :math:`{\bf a}` , ( :math:`\exp_a` ) est
  une fonction de :math:`\mathbb{R}` dans :math:`\mathbb{R}_0^+` qui à
  chaque :math:`x` fait correspondre une image notée :math:`\exp_a x` ou
  :math:`a^x` qui se définit de la manière suivante:

      -   si :math:`x` est un rationnel, c-à-d qu’il s’écrit sous la forme
          :math:`\frac{m}{t}` avec :math:`m` et :math:`t` entiers premiers entre
          eux alors :math:`a^x=\sqrt[t]{a^m}` .

On prolonge cette fonction sur :math:`\mathbb{R}` de manière continue:

      -   si :math:`x` est un irrationnel; il existe une suite de rationnels
          :math:`\{x_i\mid i \in N\}` telle que :math:`\lim_{i\rightarrow \infty}{x_i}=x` ,
          alors :math:`a^x=\lim_{i\rightarrow \infty}{a^{x_i}}`

Si un phénomène (par ex. une population) évolue de sorte que, sur des intervalles de temps égaux, il s’accroit dans la même proportion, on
dira qu’il a une **croissance exponentielle** ; il peut s’exprimer au
moyen d’une fonction exponentielle:

Appelons :math:`P(t)` la population au temps :math:`t` . Si elle est
multipliée par 2 durant l’unité de temps, on a
:math:`P(t)=P(0) . 2^t` .

De manière générale, si une quantité Q(t) évolue de manière
exponentielle et que le facteur multiplicatif par unité de temps est
a, on a :math:`\forall t:\frac{Q(t+ ?t)}{Q(t)}=` constante, en particulier :math:`\frac{Q(t+1)}{Q(t)}=a` , son équation est : :math:`Q(t)=Q(0). a^t` .


Le **logarithme de base a** ( :math:`\log_a` ) est la réciproque de la
fonction exponentielle ; c’est donc une fonction de :math:`\mathbb{R}_0^+` dans :math:`\mathbb{R}` qui à chaque :math:`x`
fait correspondre un nombre :math:`y` noté :math:`\log_a(x)` tel que :math:`a^y=x` .

Autrement dit, le logarithme en base :math:`a` d’un nombre est
l’exposant qu’il faut mettre à :math:`a` pour obtenir une puissance égale à ce nombre.

Propriétés du logarithme
-------------------------

-  :math:`\forall x,y \in \mathbb{R}_0^+`

-  :math:`\log_a(x.y)=\log_a x+\log_a y`

-  :math:`\log_a \frac{x}{y}=\log_a x-\log_a y`

-  :math:`\log_a x^y=y.  \log_a x`

Ces propriétés se démontrent en utilisant les propriétés des exposants.

Formule de changement de base
------------------------------

- :math:`\log_a x=\frac{\log_b x}{\log_b a}`
