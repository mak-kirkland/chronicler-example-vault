---
title: Óhrært Brynjuson
image: Unstirred.png
tags: [Character, Player, Nordreach]
Heritage: ['**Heritage:** Human', '**Career:** Warden']
Class: ['**Class:** Censor', '**Subclass:** Paragon']
Mother: ['Brynja']
Father: ['Halvard']
Culture: ["Secluded"]
Culture2: ["Communal"]
Culture3: ["Martial"]
Skills: [Eavesdrop, Endurance, Lead, Lift, Monsters]
Skills2: [Nature, Persuade, Read Person, Strategy]
layout:
- type: group
  render_as: columns
  keys: [Heritage, Class]
- type: header
  text: 'Culture'
  position: {above: Culture}
- type: group
  render_as: columns
  keys: [Culture, Culture2, Culture3]
- type: header
  text: 'Parents'
  position: {above: Mother}
- type: group
  render_as: columns
  keys: [Mother, Father]
- type: header
  text: 'Skills'
  position: {above: Skills}
- type: group
  render_as: columns
  keys: [Skills, Skills2]
---

**Óhrært Brynjuson** is *very* strong. He once killed an [[Aboleth]]. His secret mission is ||very secret indeed|| (click to reveal spoiler). 

# Evasion

Your evasion changes depending on what kind of armour you wear. The calculations are as follows.

- Light armour doesn’t use endurance in your Evasion Calculation.
  - 10 + Grace
- Medium Armour limits your evasion by your lowest attribute.
  - 10 + (Lowest of Grace and Endurance ×2).
- Heavy armour doesn’t use grace in your Evasion Calculation.
  - 10 + Endurance