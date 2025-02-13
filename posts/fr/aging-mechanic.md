---
author: Unintelligent Nerd
date: '2020-04-23T07:00:00.000Z'
title: 'Aging Mechanic'
description: 'Aging Mechanic'
contributors:
  - "unintelligent-nerd"
---

Vos amis gotchi sont en vie ! Comme vous, ils vieillissent — de l'enfance à l'âge adulte.

N'oubliez pas de célébrer l'anniversaire de votre lil fren ! Ils en ont également un !

<div class="headerImageContainer">
<img class="headerImage" src="/aging-mechanic/aging-mechanic.png">
<p class="headerImageText">Deckaard Caain: Restez un instant et écoutez</p>
</div>

<div class="contentsBox">

**Contenu**

<ol>
<li><a href=#rationale>Raisonnement</a></li>
<li><a href=#brs-boost>Boost de BRS</a></li>
</ol>

</div>

## Raisonnement

[La proposition d'amélioration Aavegotchi 13](/aavegotchi-improvement-proposals#add-an-aging-mechanic-to-affect-aavegotchi-rarity-scores) a introduit un mécanisme de vieillissement pour les Aavegotchis.

Les Gotchis peuvent recevoir un petit coup de pouce à leur [BRS](/rarity-farming#base-rarity-score) au fur et à mesure qu'ils vieillissent. Il s'agit de doser plus justement la différence statistique entre les Haunts et la récompense de l'engagement sur le long terme.

Cela fournit un tampon d'environ 6 mois au cours desquels les gotchis plus anciens ont un boost BRS par rapport aux gotchis nouvellement invoqués. À mesure qu'un gotchi qui vient d'être invoqué prend de l'âge, ils commence rapidement à rattraper ses homologues plus âgés.

La formule utilisée pour calculer le boost BRS est modélisée suivant les nombres de Fibonacci x 1 million mais en remplaçant le premier 0 par un 1 pour mieux s'adapter.

This solution provides for a quicker boost in the first few epochs of age, and greatly flattens over time to avoid anything too OP and allow more recently summoned gotchis to **eventually** catch up to **within a 1 BRS boost** of their older and wiser brethren. It incentivizes opening and summoning portals as opposed to sitting on them, both boosting the in-game economy as well as the scarcity of those that are still chosen to remain closed. Most of all, it is a fair system that benefits no one haunt over any other, and simply rewards long term engagement, while counteracting the effects of sudden and aggressive dilution like we are currently witnessing.

## Boost de BRS

table_brsBoost

