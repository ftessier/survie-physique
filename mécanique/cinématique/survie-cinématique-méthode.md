# Aide-mémoire — Cinématique rectiligne

## Les variables à magasiner

En lisant un problème, cherche ces cinq ingrédients sois dans ce qui t'est donné ou ce qui t'est demandé. Tu en auras toujours au moins trois :

| Symbole | Signification | Unité SI | Ce qu'on cherche dans l'énoncé |
|---------|--------------|----------|-------------------------------|
| $\Delta d$ | Déplacement | m | Une distance parcourue, une longueur de piste, « combien de mètres »... |
| $v_i$ | Vitesse initiale | m/s | « part du repos » ($v_i = 0$), « roule à ... », « passe devant un repère à ... » |
| $v_f$ | Vitesse finale | m/s | « atteint ... », « s'arrête » ($v_f = 0$), « sa vitesse au fil d'arrivée » |
| $a$ | Accélération | m/s² | « accélère à ... », « freine uniformément » ($a < 0$), « décélère » |
| $\Delta t$ | Intervalle de temps | s | « pendant ... secondes », « après ... secondes », « en combien de temps » |

### Trucs rapides

- « Part du repos » $\Rightarrow$ $v_i = 0$
- « S'arrête » ou « arrêt complet » $\Rightarrow$ $v_f = 0$
- « Vitesse constante » $\Rightarrow$ $a = 0$ (MRU, pas MRUA)
- « Freine uniformément » $\Rightarrow$ l'accélération est de signe contraire à la vitesse
- Attention aux unités : km/h $\rightarrow$ m/s, on divise par $3{,}6$
- Pour un mouvement selon deux direction, disons horizontale et verticale, résoudre le problème séparément selon chaque direction.

---

## Les cinq équations

### 1. Mouvement rectiligne uniforme

$$\Delta d = v \cdot \Delta t$$

Utile quand il n'y a **pas d'accélération**. Trois variables, trois variantes possibles.

---

### 2. Moyenne des vitesses

$$\Delta d = \frac{v_i + v_f}{2} \cdot \Delta t$$

La variable **absente** : $a$. Utile quand on connaît les deux vitesses et le temps (ou qu'on en cherche une des trois).

---

### 3. Position avec vitesse initiale

$$\Delta d = v_i \cdot \Delta t + \frac{1}{2} \cdot a \cdot (\Delta t)^2$$

La variable **absente** : $v_f$. C'est l'équation « je connais le début ».

---

### 4. Position avec vitesse finale

$$\Delta d = v_f \cdot \Delta t - \frac{1}{2} \cdot a \cdot (\Delta t)^2$$

La variable **absente** : $v_i$. C'est l'équation « je connais la fin ». Remarque le signe $-$ devant le terme en $a$.

---

### 5. Relation vitesse-déplacement

$$v_f^2 = v_i^2 + 2 \cdot a \cdot \Delta d$$

La variable **absente** : $\Delta t$. Très puissante quand le temps n'apparaît nulle part dans l'énoncé.

---

## Comment choisir son équation?

1. Identifie tes **données** (les variables connues).
2. Identifie ton **inconnue** (ce qu'on te demande).
3. Cherche l'équation où la **variable absente** est celle qui ne figure ni dans tes données ni dans ta question.
