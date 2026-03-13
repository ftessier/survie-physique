# Cinématique

Le mot vient du grec **κίνημα** (ki-nè-ma) — le mouvement (la même racine que le mot cinéma!). La cinématique, c'est littéralement la science du mouvement. Pas *pourquoi* les choses bougent (ça, c'est la dynamique, et ça vient après), juste *comment* : où, quand, à quelle vitesse.

## Pourquoi on commence par là

Parce que c'est la branche de la physique que tu vis déjà tous les jours sans le savoir. En auto, tu regardes le compteur : vitesse. Tu regardes l'heure de départ et l'heure d'arrivée : temps. Tu regardes Google Maps : distance. Tu as déjà les trois concepts dans ta tête sans avoir ouvert un seul manuel.

L'accélération, c'est un cran plus abstrait — c'est le *changement* de la vitesse, un calcul sur un calcul. Mais tu la connais dans ton corps : c'est ce qui te pousse dans ton siège quand le feu passe au vert, ou ce qui te projette vers l'avant quand le conducteur freine sec. On peut la ressentir avant de la calculer, et c'est exactement pour ça qu'on commence ici.

## Un détail pas si anodin

Quand on fait de la cinématique, on tient certaines choses pour acquises. Le temps passe de la même façon pour tout le monde. L'espace est le même partout. Une seconde ici, c'est une seconde là-bas. Un mètre ici, c'est un mètre là-bas. Ça semble tellement évident que ça ne vaut même pas la peine d'en parler.

Sauf que ça dépend de ta technologie. Aujourd'hui, ton cellulaire se synchronise à la nanoseconde avec des serveurs partout dans le monde via NTP (*network time protocol*). Le temps commun te semble naturel — tout le monde a la même heure affichée au même instant. Ton odomètre t'affiche ta vitesse instantanée en temps réel, comme si c'était banal.

Mais quand Newton a formalisé tout ça au 17e siècle, personne n'avait d'outil capable de mesurer une vitesse *instantanée*. Le concept existait en mathématiques, mais pas dans les mains. L'idée d'un temps absolu et d'un espace absolu, c'était un *choix* philosophique — hérité de Platon, consolidé par Newton — pas une évidence. Ça avait l'air raisonnable, et ça a tenu pendant deux cents ans. Jusqu'à Einstein, mais ça c'est une autre histoire.

Pour l'instant, Newton a raison, ton cellulaire est synchronisé, et on a des problèmes à résoudre.

## Une note sur la notation

Dans ton cours, tu vas probablement voir le déplacement écrit $\Delta d$. C'est la notation standard au secondaire au Québec, et c'est celle qu'on utilise dans les problèmes ici pour que tu ne sois pas perdu en classe. Mais il faut qu'on en parle, parce qu'elle pose un vrai problème.

Le symbole $\Delta$ signifie « la différence entre la valeur finale et la valeur initiale ». Quand on écrit $\Delta t$, c'est clair : c'est $t_f - t_i$, la différence entre deux instants. Quand on écrit $\Delta v$, c'est $v_f - v_i$, la différence entre deux vitesses. Parfait.

Mais la variable $d$, dans cette notation, évoque déjà le mot *déplacement* — c'est-à-dire une différence entre deux positions! Écrire $\Delta d$, c'est comme écrire « le changement du changement de position ». Ça ne veut rien dire de cohérent.

Et il y a un deuxième piège : la lettre $d$ peut aussi évoquer le mot *distance*, qui est un concept différent du déplacement. Le déplacement est un vecteur (qui comporte une grandeur et une direction; une "flèche" de la position initiale à la position finale, peu importe le chemin). La distance est un *scalaire* (un simple nombre sans direction, la longueur totale du trajet parcouru). Ainsi un aller-retour au dépanneur donne un déplacement nul mais une distance bien réelle. Même lettre, deux idées opposées. Ça n'arrange rien.

**La notation propre** utilise $x$ pour la position. Tout devient symétrique et limpide :

| Quantité | Initiale | Finale | Différence |
|----------|----------|--------|------------|
| Temps | $t_i$ | $t_f$ | $\Delta t = t_f - t_i$ |
| Position | $x_i$ | $x_f$ | $\Delta x = x_f - x_i$ |
| Vitesse | $v_i$ | $v_f$ | $\Delta v = v_f - v_i$ |

Le déplacement, c'est maintenant $\Delta x$. Le $\Delta$ a exactement le même sens partout. Pas d'ambiguïté, pas de collision avec la distance, et chaque variable a sa paire initiale-finale. C'est la notation utilisée dans la plupart des manuels universitaires et c'est celle que tu verras si tu continues en sciences.

En attendant, on joue le jeu du $\Delta d$ dans les problèmes — mais maintenant tu sais ce qu'il y a derrière.

## Contenu

- [Théorie: Démonstration des équations](survie-cinématique-théorie.md)
- [Méthode: comment résoudre des problèmes](survie-cinématique-méthode.md)
- [Exercices 1 — Mouvement rectiligne uniforme](survie-cinématique-exercices-01.md)
- [Exercices 2 — Déplacement par la moyenne des vitesses](survie-cinématique-exercices-02.md)
- [Exercices 3 — Équation de position en fonction du temps](survie-cinématique-exercices-03.md)
- [Exercices 4 — Équation de position avec la vitesse finale](survie-cinématique-exercices-04.md)
- [Exercices 5 — Relation vitesse-déplacement (sans le temps)](survie-cinématique-exercices-05.md)
- [Exercices 6 — Problèmes avancés](survie-cinématique-exercices-06.md)
- [Exercice — Le boss final](survie-cinématique-exercices-boss-final.md)
- [Exercice — La vraie vie](survie-cinématique-exercices-vraie-vie.md)
