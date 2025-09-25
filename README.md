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
- N'est jamais utilisé lors de la rotation optimisée

### Skyfall

![Skyfall](assets/rmb.png)

- Priorité d'amélioration: 3ème
- Compétence principale pour générer des stacks de Sharp et proc Chasing Step

### Typhoon Cleave

![Typhoon Cleave](assets/r.png)

- Priorité d'amélioration: pas besoin d'améliorer
- Utilisé pour générer du Courage, pas pour les dégâts

### Falcon Toss

![Falcon Toss](assets/q.png)

- Priorité d'amélioration: 4ème
- Généralement pas utilisé en rotation, utilisé une seule fois durant Wind Fury quand Azure Sever est disponible

### Instant Edge

![Instant Edge](assets/e.png)

- Priorité d'amélioration: 1er
- L'une des sources principales de dégâts pour la classe, consomme des stacks de Sharp à l'utilisation et consomme des stacks de Chasing Step lorsqu’un ennemi est touché
- Permet de recharger Sharp Impact
- Durant Wind Fury la compétence déclenche une tornade lorsqu'un ennemi est touché
  - Si la compétence est utilisée en l'air, une tornade sera créée
  - Si la compétence est utilisée au sol, deux tornades seront créées (mais l'animation sera plus longue)
- Cette compétence est utilisée pour déclencher Instant Edge Combo

### Galeform

![Galeform](assets/4.png)

- Priorité d'amélioration: 2ème
- Utilisé pour activer le buff Galeform, possède 2 charges avec un cooldown de 30 secondes
- Améliorer cette compétence augmente le buff de dégâts, affectant toutes les autres compétences

### Sharp Impact

![Sharp Impact](assets/c.png)

- Priorité d'amélioration: 4ème
- Les dégâts de la compétence sont négligeable, elle est utilisée surtout pour activer le buff Wind Fury.
- Quand la compétence est lancée au sol, votre personnage se téléporte d'abord au dessus de la cible avant de s'écraser au sol. Cette animation initiale est longue et peut être entièrement évitée en sautant avant de lancer la compétence. Cette technique "jump cancel" est incorporée dans la rotation.

## Ressources de classe

### Courage

![Courage](assets/courage.png)

- Recharge naturellement au rythme de 3 Courage / seconde
- Quand le buff Galeform est actif, recharge naturellement 7 Courage / seconde additionnel
- Quand le buff Wind Fury est actif, la recharge additionnelle de Galeform passe à 10 Courage / seconde
- Les ticks de recharge de Galeforme sont indépendants des ticks de régénération naturelle.

### Sharp

![Sharp](assets/sharp.png)

- Chaque stack dure 10 secondes, quand le timer arrive à zéro un stack est retiré. Si cela arrive, cela est considéré comme un stack dépensé pour charger Sharp Impact
- Chaque stack donne +5% d'attaque, n'avoir qu'un seul stack de Sharp est suffisant pour donner le même bonus d'attaque que si les stacks étaient complets. Cela veut dire que (en assumant que le maximum de Sharp est augmenté à 6 via les nodes passifs) n'avoir qu'un seul stack de Sharp donne: 5% x 6 = 30% bonus d'attaque
- Due à cette méchanique, il est nécessaire de toujours garder au moins un stack de Sharp en tout temps. Cela vaut également pour les DoTs comme les tornades car les dégâts sont calculés pour chaque tick de dégât plutôt que snapshot à la création de la tornade en elle-même.

### Chasing Step

| 1 Stack | 2 Stacks |
|-----------|-----------|
| ![1 Stack](assets/jj1.png)  | ![2 Stack](assets/jj2.png)  |
