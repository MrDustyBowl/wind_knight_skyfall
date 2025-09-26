# BPSR: Guide compréhensif de la classe Wind Knight (spec Skyward)
(Ceci est une traduction française du guide rédigé par s.now_ (s.now25))
- [Introduction](chapter1.md)
- [Compétences](chapter2.md)
- [Chapter 3: Endgame](chapter3.md)

---

## Version vidéo de ce guide (en anglais)
[https://youtu.be/rotHMENL6Ek](https://youtu.be/rotHMENL6Ek)

## Introduction

Le Skyward Wind Knight est un DPS de mêlée avec une mécanique unique où vous restez en l’air la moitié du temps pendant le combat. Quand vous êtes en l’air vous pouvez éviter beaucoup de dégâts au sol (y compris d’attaques de boss). La classe possède d’excellents dégâts de zone (AoE) et des dégâts monocible respectables, mais elle n’a aucune compétence d’interruption ni de regroupement de mobs.

Cette classe utilise de l’équipement basé sur la Force, le même type d’équipement que les deux classes tank. Si vous souhaitez aussi jouer tank en parallèle sans trop optimiser le tank, il vous suffira simplement de farmer une arme de tank et vous serez prêt.

Cette classe n’est pas la meilleure classe DPS. Si vous voulez jouer une classe DPS de premier plan, je vous recommande plutôt de jouer Marksman (Bow).

## Compétences

### Attaque de base (clique gauche de la souris)

- Priorité d'amélioration: pas besoin d'améliorer
- N'est jamais utilisé lors de la rotation optimisée.

### Skyfall

![Skyfall](assets/rmb.png)

- Priorité d'amélioration: 3ème
- Compétence principale pour générer des stacks de Sharp et proc Chasing Step.

### Typhoon Cleave

![Typhoon Cleave](assets/r.png)

- Priorité d'amélioration: pas besoin d'améliorer
- Utilisé pour générer du Courage, pas pour les dégâts.

### Falcon Toss

![Falcon Toss](assets/q.png)

- Priorité d'amélioration: 4ème
- Généralement pas utilisé en rotation, utilisé une seule fois durant Wind Fury quand Azure Sever est disponible.

### Instant Edge

![Instant Edge](assets/e.png)

- Priorité d'amélioration: 1er
- L'une des sources principales de dégâts pour la classe, consomme des stacks de Sharp à l'utilisation et consomme des stacks de Chasing Step lorsqu’un ennemi est touché.
- Permet de recharger Sharp Impact.
- Durant Wind Fury la compétence déclenche une tornade lorsqu'un ennemi est touché.
  - Si la compétence est utilisée en l'air, une tornade sera créée.
  - Si la compétence est utilisée au sol, deux tornades seront créées (mais l'animation sera plus longue).
- Cette compétence est utilisée pour déclencher Instant Edge Combo.

### Galeform

![Galeform](assets/4.png)

- Priorité d'amélioration: 2ème
- Utilisé pour activer le buff Galeform, possède 2 charges avec un cooldown de 30 secondes.
- Améliorer cette compétence augmente le buff de dégâts, affectant toutes les autres compétences.

### Sharp Impact

![Sharp Impact](assets/c.png)

- Priorité d'amélioration: 4ème
- Les dégâts de la compétence sont négligeable, elle est utilisée surtout pour activer le buff Wind Fury.
- Quand la compétence est lancée au sol, votre personnage se téléporte d'abord au dessus de la cible avant de s'écraser au sol. Cette animation de téléportation initiale est longue mais elle peut être entièrement évitée en sautant avant de lancer la compétence. Cette technique "jump cancel" est incorporée dans la rotation.

## Ressources de classe

### Courage

![Courage](assets/courage.png)

- Recharge naturellement au rythme de 3 Courage / seconde.
- Quand le buff Galeform est actif, recharge naturellement 7 Courage / seconde additionnel.
- Quand le buff Wind Fury est actif, la recharge additionnelle de Galeform passe à 10 Courage / seconde.
- Les ticks de recharge de Galeform sont indépendants des ticks de régénération naturelle.

### Sharp

![Sharp](assets/sharp.png)

- Chaque stack dure 10 secondes, quand le timer arrive à zéro un stack est retiré. Si cela arrive, cela est considéré comme un stack dépensé pour charger Sharp Impact.
- Chaque stack donne +5% d'attaque, n'avoir qu'un seul stack de Sharp est suffisant pour donner le même bonus d'attaque que si les stacks étaient complets. Cela veut dire que (en assumant que le maximum de Sharp est augmenté à 6 via les nodes passifs) n'avoir qu'un seul stack de Sharp donne: 5% x 6 = 30% bonus d'attaque.
- Due à cette méchanique, il est nécessaire de toujours garder au moins un stack de Sharp en tout temps. Cela vaut également pour les DoTs comme les tornades car les dégâts sont calculés pour chaque tick de dégât plutôt que snapshot à la création de la tornade en elle-même.

### Chasing Step

| 1 Stack | 2 Stacks |
|-----------|-----------|
| ![1 Stack](assets/jj1.png)  | ![2 Stack](assets/jj2.png)  |

- Un stack de Chasing Step est généré quand Skyfall inflige des dégâts critiques, jusqu'à 2 stacks max.
- Quand un stack est dépensé par Instant Edge, il génère 1 stack de Sharp.
- Quand un stack est dépensé par Instant Edge, il double la charge de Sharp Impact.
  - Une utilisation d'Instant Edge à 3 stack de Sharp charge 15% de Sharp Impact, avec un stack de Chasing Step cela augmente à 30%.
- C'est l'une des ressources les plus importantes, permettant d'accélérer la charge de Sharp Impact, plus de détails dans la partie Rotation.

## Buff clés

### Wind Fury

- Buff de 15 secondes déclenché par Sharp Impact, augmente les dégâts infligés de 15%.
- Augmente la régénération de Courage du buff Galeform.
- Falcon Toss devient Azure Sever pour la première utilisation durant le buff.
- Instant Edge et Azure Sever génèrent une Tornade durant le buff.
  - Si Instant Edge est lancé en étant au sol, la compétence touche l'ennemi deux fois et crée deux Tornades

### Galeform

- Buff de 15 secondes qui augmente la régénération de Courage et l'attaque (conversion de force), quand le buff est actif la barre de Courage sera entourée de vert.

![Galeform](assets/galeformbuff.png)

### Wind and Thunder

-Quand le buff se dissipe, il applique un second buff: Wind and Thunder. Galeform doit expirer naturellement à la fin de son timer pour déclencher ce second buff. Si Galeform est retiré ou rafraîchit avant qu'il ne termine, Wind and Thunder ne sera pas appliqué.

![Wind and Thunder](assets/windnthunder.png)

## Arbre de compétence passive

### Noeuds clés

#### Tornade

![Tornado](assets/tornado.png)
![Tornado1](assets/tornado1.png)

La description en jeu de la Tornade n'est pas complète. Voici en détail comment la Tornade fonctionne.
- Chaque Tornade reste sur le terrain pendant 3 secondes, délivrant 1 tick de dégât par cible par seconde. Chaque tick de dégâts est équivalent à 350% de l'attaque, cela signifie que la tornade inflige jusqu'à 1050% de multiplicateur d'attaque en dégât par cible (en assumant que tous les ticks de dégâts sont infligés à la cible).
  - Après la mise à jour d’équilibrage de classe du 28/08, les patch notes indiquent que chaque Tornade verra ses dégâts réduits de 20% après chaque coup, jusqu’à un minimum de 40% de l’attaque. Cela signifie que le multiplicateur de dégâts de chaque Tornade peut passer de 1050% à 40% s’il touche suffisamment d’ennemis (scénario non monocible).
  - Mais en réalité, ce qui est implémenté en jeu n’est pas conforme aux patch notes : la réduction appliquée par coup est en fait de 40%, et non de 20%. Nous ne savons pas encore si cela sera corrigé pour correspondre aux patch notes, ou si la description sera simplement ajustée pour refléter ce qui est réellement en jeu.
  - Il ne peut y avoir que 3 Tornades sur le terrain à la fois. Les compétences ne déclencheront pas de Tornades supplémentaires et ne rafraîchiront pas les Tornades existants lorsqu’il y en a déjà 3 en jeu.
  - Les dégâts des Tornades ne se basent ni sur le niveau des compétences, ni sur les dégâts de Mêlée, ni sur les dégâts de Skill Expertise.
  - La Tornade est l’une des principales sources de dégâts. Les compétences qui déclenchent des Tornades sont expliquées dans la section Wind Fury.

#### Instant Edge Combo

Après la mise à jour d’équilibrage de classe du 28/08, ce noeud est passé d’un taux fixe de 15% à un taux identique à celui de Lucky Hit du personnage, c’est-à-dire le pourcentage de Luck. Les dégâts seront alors calculés comme les dégâts de Instant Edge (avec tous ses multiplicateurs applicables) × le multiplicateur de dégâts Lucky Hit. Sur mon personnage avec un set 4 pièces d’équipement de classe niveau 60 + une arme niveau 70, ce multiplicateur est d’environ 100%, ce qui signifie qu’à chaque proc, Instant Edge inflige 2x ses dégâts.

| Avant | Après |
|-----------|-----------|
| ![InstantEdgeComboBefore](assets/iecombo.png)  | ![InstantEdgeComboAfter](assets/cnlj.png)  |

#### Azure Sever

![Sharp Long Breath](assets/st_azure.png)

Permet d'utiliser Azure Sever, générant 3 stacks de Sharp quand la compétence touche un ennemi, voir Falcon Toss et Wind Fury pour plus d'infos.

#### Chasing Step

![Pursuit Stance](assets/st_chasingstep.png)

Permet d'utiliser Chasing Step.

![Sharp Pursuit](assets/st_chasingsteprefund.png)

Génère 1 stack de Sharp quand Chasing Step est consommé.

#### Sharp Impact

![Air Dance Strike](assets/st_sharpimpact3.png)

- Augmente la génération de Courage de Galeform.
- Génère 3 stacks de Sharp quand Sharp Impact touche un ennemi

![Typhoon: Sharp Impact](assets/st_sharpimpact6.png)

- Le jeu n’explique pas bien ce point : ce noeud fait en sorte que Sharp Impact inflige un coup supplémentaire, et ce coup supplémentaire accorde 3 Sharp en plus des 3 obtenus via Air Dance Strike.
- L’objectif principal de prendre ce noeud est donc d’avoir directement 6 Sharp après chaque Sharp Impact.

#### Wind Fury

![Wind Fury](assets/st_windfury.png)

Permet de bénéficier de Wind Fury.

![Sharp Advancement](assets/st_windfury50.png)

Permet de bénéficier de la double charge de Sharp Impact avec Instant Edge

### Build arbre de compétence

#### Build recommandé

Le bleu met en évidence le cœur du build. Avec un équipement niveau 60 (arme 70), vous devez prendre le chemin jaune pour augmenter les dégâts des Tornades. Même si les dégâts des Tornades ont été nerfés lors de la mise à jour d’équilibrage de classe du 28/08, cela reste malgré tout la source de dégâts la plus importante.

#### Autres builds

Il existe quelques builds assez originaux pour cette classe. Je ne les recommande pas ici car ces builds vont à l’encontre de l’idée que les devs ont de cette classe (vous misez sur des stats que le jeu ne conseille pas), et il faudrait investir dans d’autres Imagines (gold).

Si ces builds originaux deviennent trop puissants et attirent l’attention des devs, ils seront équilibrés et nerfés tout comme la meta Tornade. J’aimerais éviter que des joueurs viennent me dire qu’ils se sont fait arnaquer après avoir investi dans des Imagines devenus inutiles pour la classe parce qu’ils ont suivi mon guide pour un build original et que les devs l’ont nerf.

Cela étant dit, si vous êtes quand même intéressés, vous pouvez me contacter et je pourrai vous expliquer ces autres builds en privé.

## Rotation

La rotation pour le build recommandé est en réalité très simple :

1. Utilisez toutes les imagines disponibles, puis Galeform.
2. Faites un jump cancel pour Sharp Impact (note : génère 6 Sharp grâce à ce noeud).
3. Instant Edge au sol, puis 3x Skyfall.
4. Instant Edge en l'air → Instant Edge au sol.
5. Azure Sever, puis faites 1 ou 2 Skyfall jusqu’à atteindre 6 stacks de Sharp (note : Azure Sever génère 3 Sharp, grâce à ce noeud).
6. Instant Edge en l'air → Instant Edge au sol.

Tant que vous obtenez 2 procs de Chasing Step sur les 5 Skyfalls des étapes 3 et 5, votre Sharp Impact sera rechargé à la fin de l’étape 6. Vous pourrez alors recommencer la rotation à partir de l’étape 1 ou 2. C’est pour cette raison que vous n’avez besoin que d’environ 40% de crit rate (2 / 5 = 0,4) pour exécuter cette rotation sans problème.

### Gérer le Courage et autres nuances

Il y a quelques nuances dans la gestion de Courage, notamment concernant l’utilisation de Galeform et de l’ultime (Typhoon Cleave). Tout d’abord, vous devez retenir trois chiffres : 35, 70 et 105. Ce sont les valeurs de Courage nécessaires pour lancer respectivement 1x, 2x et 3x Skyfall.

- Supposons que vous soyez actuellement à l’étape 2 de la rotation, et que votre Courage soit supérieur à 105. Vous savez alors que vous pouvez continuer la rotation jusqu’à la fin de l’étape 3. Si à l’étape 3 vous obtenez deux procs de Chasing Step sur les 3x Skyfall, alors vous savez qu’il ne vous restera qu’à faire 1 Skyfall à l’étape 5, soit 35 Courage. À ce moment, vous pouvez vérifier si vous avez 35 Courage pendant l’exécution de l’étape 4, et décider si vous devez utiliser Galeform avant l’étape 5. L’idée ici est de retarder l’utilisation de Galeform suffisamment pour ne pas atteindre le maximum de Courage. Quand vous êtes chanceux (obtenant deux procs de Chasing Step), vous pouvez généralement retarder encore plus, car vous n’avez pas besoin de faire les cinq Skyfall. Quand vous êtes malchanceux (aucun proc de Chasing Step sur les cinq Skyfall), vous devrez probablement utiliser l’ult pour récupérer du Courage afin de ne pas briser complètement la rotation.
- À l’étape 5, vous pouvez alterner l’ordre de Azure Sever et de Skyfall en fonction de votre Courage et du temps restant du buff Galeform.
  - Si votre Courage est sur le point d’atteindre le cap de 130, vous devez utiliser Skyfall pour atteindre 3 Sharp stacks d’abord, puis utiliser Azure Sever. Cela évite de gaspiller du Courage.
  - Si le buff Galeform est sur le point de se terminer, vous devez utiliser Azure Sever en premier afin que ses dégâts soient augmentés.
  - S’il n’y a actuellement aucun buff Galeform actif et que votre Courage est faible, vous pouvez utiliser Galeform, puis Azure Sever, puis Skyfall pour remplir les Sharp stacks restants. Cela garantit que les dégâts de Azure Sever sont boostés et que vous avez suffisamment de temps pour régénérer du Courage pour Skyfall.
  - S’il y a déjà 3 Tornades sur le terrain, vous pouvez faire Skyfall > Azure Sever > Skyfall pour éviter que le Tornade d’Azure Sever ne soit pas généré à cause du cap de Tornades (expliqué dans la section Tornades).

Il existe beaucoup, beaucoup d’autres scénarios. À force de jouer, vous commencerez à ressentir ce que vous devez faire.

## Équipement et stats

### Stats

#### Critique

Il faut 40% de chance de coup critique pour pouvoir exécuter la rotation telle qu’expliquée dans la section Rotation. Une fois 40% atteint, accumuler davantage de chance de critique n’apporte pas autant de valeur que d’autres statistiques comme la célérité (haste).

Célérité (haste)

Le but d’accumuler de la célérité est d’obtenir une vitesse d’attaque plus élevée, chaque pourcentage de célérité nous donnant 1,6% de vitesse d’attaque.

Mais comme la conversion de la valeur brute de célérité en pourcentage subit des rendements décroissants, alors que l’augmentation du pourcentage de vitesse d’attaque est linéaire, il est toujours préférable de privilégier directement la vitesse d’attaque si possible.

Sources d’augmentation directe du pourcentage de vitesse d’attaque :
- Équipement violet
- Modules
Nous voulons atteindre au moins 20% de vitesse d’attaque, ce qui nous permettra de terminer confortablement 1 rotation pendant la durée de 15s de Wind Fury, maintenant ainsi 100% de temps actif sur Wind Fury.

Personnellement, je recommande de viser une vitesse d’attaque supérieure à 20%, car il nous arrive encore d’atteindre le cap de Courage. Une vitesse d’attaque plus élevée permettra de convertir le Courage gaspillé en dégâts. Bien qu’il soit attendu qu’il existe un point où la vitesse d’attaque sera trop élevée et que la génération de ressources ne pourra pas suivre, je ne sais pas encore où se situe ce point.

Pour référence, mon personnage avec un équipement niveau 60 est à 25% de vitesse d’attaque, et avec l’équipement niveau 80 à venir, il est prévu que ce soit encore plus élevé.

#### Luck

Avec la mise à jour d’équilibrage de classe du 28/08, la Luck va désormais scaler un peu, voir la section sur Instant Edge Combo.

Actuellement, je n’ai pas assez de données pour dire s’il existe des breakpoints ou un sweet spot à atteindre. Pour l’instant, je recommande donc simplement de viser un set de classe 6 pièces et de ne pas chercher à augmenter la Luck de manière spécifique.

### Équipement Lv60 & Gemmes

- Obtenez un set de classe 6 pièces
- Atteignez 40% de chance de coup critique
- Atteignez 20% de vitesse d’attaque
- Placez vos gemmes et refondez votre 3ème stat secondaire sur l’équipement en fonction de la stat qui vous manque. Si vous avez déjà 40% de chance de coup critique et 20% de vitesse d’attaque, je recommande de viser la célérité pour augmenter encore la vitesse d’attaque.

### Équipement Lv80 & Gemmes

- Obtenez un set de classe 4 pièces
- A FAIRE: mettre à jour crit, vitesse d'attaque cible

## Imagines

### Imagines pour Whales

| Lv5 Muku Chief | Lv5 Goblin King |
|-----------|-----------|
| ![Muku Chief](assets/muku.png)  | ![Goblin King](assets/goboking.png)  |

### Imagines pour F2P

| Lv(0-3) Muku Chief | Lv5 Muku Scout |
|-----------|-----------|
| ![Muku Chief](assets/muku.png)  | ![Muku Scout](assets/mukuscout.png)  |

- Le Muku Scout surpasse largement le Storm Goblin Warrior. Tant que la rotation est correctement exécutée, le buff du Muku Scout aura un temps actif de 100%.
- La description du Muku Scout n’est pas très précise, mais en gros, il suffit d’infliger des dégâts au moins 10 fois toutes les 5 secondes pour maintenir le buff, ce qui est facilement réalisable avec mes stats et rotation recommandées.

## Modules

Ma recommandation, triée par priorité :
- Force
- Dégâts Elites
- Agilité
  - Donne des dégâts physiques fixes, de l’agilité et une augmentation des dégâts physiques. L’agilité augmente également la célérité pour cette classe.
- Vitesse d'attaque
  - Priorité plus haute si votre vitesse d’attaque est inférieure à 20%

Non recommandé :
- Chance de coup critique
  - Le module chance de coup critique vous donne des PV, et le niveau 6 apporte 12% de dégâts critique. En supposant que vous ayez Muku Chief Lv3 (19% dégâts critique) et une chance de coup critique de 45%, l’augmentation réelle de ce module serait seulement de: ((150 + 19 + 12) / (150 + 19) - 1) * 45% = 3.2%. Si votre chance de coup critique est plus bas ou le niveau de Muku Chief plus élevé, l’augmentation serait encore plus faible.

Bien que cette liste soit triée par priorité, si vous pouvez obtenir 3 modules de niveau 6 de priorité plus faible, c’est toujours mieux que d’avoir des modules de niveau 5 de haute priorité. Concentrez-vous d’abord sur l’obtention de 2 modules niveau 6, puis suivez la liste de priorité si vous pouvez choisir, et enfin visez 666 ou 665 comme objectif final.
