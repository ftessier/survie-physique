# Démonstration des équations de la cinématique rectiligne

## Point de départ : trois fondamentaux

Toutes les équations du mouvement rectiligne uniformément accéléré (MRUA), c'est-à-dire lorsque **l'accélération est constante** (incluant les cas sans accélération, $a=0$) découlent de trois idées simples.

### L'accélération uniforme

L'accélération (constante) est le taux de changement de la vitesse :

$$a = \frac{v_f - v_i}{\Delta t}$$

On peut isoler $v_f$ pour obtenir une relation qu'on utilisera souvent :

$$v_f = v_i + a \cdot \Delta t \quad\quad{[0]}$$

### La vitesse moyenne

Quand l'accélération est constante, la vitesse change de manière linéaire (elle augmente ou diminue au même rythme à chaque seconde). La vitesse moyenne est donc exactement à mi-chemin entre la vitesse initiale et la vitesse finale :

$$v_{\text{moy}} = \frac{v_i + v_f}{2}$$

### Le déplacement

Par définition, le déplacement est la vitesse moyenne multipliée par le temps :

$$\Delta d = v_{\text{moy}} \cdot \Delta t$$

---

## Équation 1 — Mouvement rectiligne uniforme

Quand il n'y a pas d'accélération ($a = 0$), la vitesse ne change pas : $v_i = v_f = v$. La vitesse moyenne est simplement $v$, et on obtient directement :

$$\boxed{\Delta d = v \cdot \Delta t} \quad\quad{[1]}$$

C'est un cas particulier de tout ce qui suit.

---

## Équation 2 — Moyenne des vitesses

On combine les deux définitions du point de départ sans aucune manipulation. Le déplacement est la vitesse moyenne multipliée par le temps, et la vitesse moyenne est la demi-somme des vitesses :

$$\boxed{\Delta d = \frac{v_i + v_f}{2} \cdot \Delta t} \quad\quad\quad{[2]}$$

Variable absente : $a$.

C'est l'équation mère. Les trois prochaines en découlent par substitution.

---

## Équation 3 — Position avec vitesse initiale

On veut éliminer $v_f$ de [2]. On utilise [0] :

$$v_f = v_i + a \cdot \Delta t$$

On substitue dans [2] :

$$\Delta d = \frac{v_i + (v_i + a \cdot \Delta t)}{2} \cdot \Delta t$$

On simplifie le numérateur :

$$\Delta d = \frac{2 \cdot v_i + a \cdot \Delta t}{2} \cdot \Delta t$$

On distribue :

$$\boxed{\Delta d = v_i \cdot \Delta t + \frac{1}{2} \cdot a \cdot (\Delta t)^2} \quad\quad{[3]}$$

Variable absente : $v_f$.

---

## Équation 4 — Position avec vitesse finale

On veut maintenant éliminer $v_i$ au lieu de $v_f$. On réarrange [0] :

$$v_i = v_f - a \cdot \Delta t$$

On substitue dans [2] :

$$\Delta d = \frac{(v_f - a \cdot \Delta t) + v_f}{2} \cdot \Delta t$$

On simplifie le numérateur :

$$\Delta d = \frac{2 \cdot v_f - a \cdot \Delta t}{2} \cdot \Delta t$$

On distribue :

$$\boxed{\Delta d = v_f \cdot \Delta t - \frac{1}{2} \cdot a \cdot (\Delta t)^2} \quad\quad{[4]}$$

Variable absente : $v_i$.

On remarque que c'est exactement [3] avec $v_f$ à la place de $v_i$ et un signe $-$ à la place du signe $+$. Ce n'est pas une coïncidence : les deux équations sont des images miroir, l'une regardant vers l'avant, l'autre vers l'arrière.

---

## Équation 5 — Relation vitesse-déplacement

On veut éliminer le temps $\Delta t$. On part de [0] et on isole $\Delta t$ :

$$\Delta t = \frac{v_f - v_i}{a}$$

On substitue dans [2] :

$$\Delta d = \frac{v_i + v_f}{2} \cdot \frac{v_f - v_i}{a}$$

On reconnaît au numérateur un produit de la forme $(a+b)(a-b) = a^2 - b^2$ :

$$\Delta d = \frac{v_f^2 - v_i^2}{2a}$$

On multiplie les deux côtés par $2a$ et on réarrange :

$$\boxed{v_f^2 = v_i^2 + 2 \cdot a \cdot \Delta d} \quad\quad{[5]}$$

Variable absente : $\Delta t$.

---

## Vue d'ensemble

Tout repose sur deux idées : la définition de l'accélération et le fait que la vitesse moyenne est la demi-somme des vitesses extrêmes. À partir de là, chaque équation est obtenue en éliminant une variable différente par simple substitution algébrique. Il n'y a donc pas cinq équations indépendantes à mémoriser — il y a une seule logique à comprendre.
