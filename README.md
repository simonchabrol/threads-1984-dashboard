# Threads (1984) — Post-Nuclear UK: Geo-Agricultural Analysis

> **A critical, data-driven examination of the BBC film *Threads* (1984) through the lens of agricultural geography, institutional resilience, and post-collapse governance.**

---

## Overview

This project is an interactive HTML dashboard accompanying a trilogy of analytical essays on the BBC film *Threads* (1984), which dramatises the aftermath of a nuclear attack on the United Kingdom. Rather than treating the film as a settled reference on nuclear war consequences — as much of the scientific, academic and journalistic literature does — these analyses interrogate its internal logic: its geographic premises, its agricultural assumptions, its narrative choices, and the ethical implications of its worldview.

The result is an inversion of the film's nihilist message. By applying agricultural statistics, geographic data, fuel logistics and historical precedent to the film's own scenario, the analysis reveals that the final scenes of *Threads* — school, hospital, coal extraction, electricity — are not miraculous outliers but the **logically inevitable outcome of the UK's agricultural geography**.

The dashboard is a single self-contained HTML file with no external dependencies at runtime. It is bilingual (French / English) and covers nine analytical panels.

---

## Contents

```
threads_v8.html          Main interactive dashboard (self-contained, ~900 KB)
UK_THREADS_book__1_.png  Agricultural map — French version (UK 1985–1997)
UK_THREADS_book__2_.png  Agricultural map — English version (UK 1985–1997)
README.md                This file
```

---

## The Three Articles

**Article I — UK 1984–1985: The fuel crisis and societal collapse**
A detailed reconstruction of the first year following the fictional nuclear attack of 26 May 1984. The analysis quantifies the UK's strategic fuel stocks (approximately 9 million usable barrels on Day 0, after accounting for destruction, EMP damage and inaccessibility), models the daily consumption by phase (generators, military vehicles, mechanised harvest), and traces the collapse cascade to its actual cause: not the bombs, but the "work-for-food" rationing mechanism introduced by the authorities.

**Article II — UK 1985–1994: The unexplained narrative leap**
*Threads* jumps ten years without explanation. The final scenes show a structured society — school, hospital, public lighting, coal extraction, a steam tractor — that presupposes organised agriculture, regional governance, and coordinated logistics. This article reconstructs what must have happened during that decade, using UK agricultural statistics, coal basin geography, and historical analogues (the Portuguese Carnation Revolution, the dissolution of the Soviet Union, Roman imperial fragmentation).

**Article III — Reflections: ethics, human dignity, agricultural resilience**
A synthesis of the two previous articles, examining the ethical dimension of the film's choices: the inversion by which resilience is coded as degradation, the refusal to imagine competence or coordination as survival strategies, and the film's geographic inconsistency (Buxton, in the Peak District peat moorlands, is almost certainly the worst possible location in England to film a post-nuclear agricultural recovery).

---

## Dashboard Panels

| Panel | Content |
|---|---|
| Introduction | Project overview, trilogy synopsis, three central analytical questions |
| Timeline | Chronological reconstruction, 26 May 1984 to 1997, filterable by phase |
| Data | Charts: fuel depletion, demographics, harvest loss cascade, caloric rations, agricultural yields |
| Agricultural map | Bilingual FR/EN interactive map with pan, zoom, and regional focus |
| Rump States | Analysis of the four post-collapse regional governance entities |
| New governance | The "institutional merger" thesis: how civil servants, military and agricultural experts formed the nucleus of reconstruction |
| Agricultural tools | Phase-by-phase inventory of tools necessary for post-nuclear farming, from combine harvesters to hand mills and forges |
| Alternative scenario | Quantified consequences of abandoning East England (−54% grain area, maximum supportable population of 2–4M) |
| Critical analysis | Four analytical axes and responses to common counter-arguments |
| Sources | Primary sources and methodological transparency |

---

## The Agricultural Map

The maps (`UK_THREADS_book__1_.png` for French, `UK_THREADS_book__2_.png` for English) are original analytical productions based on:

- Agricultural Land Classification UK (1983 MAFF data)
- British cereals plains/lowlands distribution
- UK coalfield geography
- Wytch Farm and North Sea oil field data
- The "rump state" hypothesis (four regional entities: Midlands/East England, Central Scotland, Kent, South-West England)

The maps show mechanised agricultural zones (red circles), manual/animal-traction zones (white circles), coalfields (halftone), fuel and machinery flows (solid arrows), livestock flows (dotted arrows), and the two critical boundary lines (Glasgow/Edinburgh line; Newport/Ipswich line).

The dashboard embeds both images as compressed base64 data. The FR/EN language toggle in the top bar switches both the interface text and the map simultaneously.

---

## Technical Notes

The dashboard is a **single HTML file** with no build step and no external runtime dependencies (Chart.js and Google Fonts load from CDN on first open). It can be opened directly in any modern browser.

**Features:**
- FR/EN language toggle (all text, map images, chart labels)
- Interactive map: scroll-to-zoom, drag-to-pan, regional zoom buttons
- Timeline filter by phase (Critical / Transition / Reconstruction / Stabilisation)
- Chart.js data visualisations (fuel depletion, demographics, harvest cascade, caloric rations, yield comparison)
- Tooltip-on-hover for all map zones
- Nine navigable panels via tab bar

**Browser compatibility:** Any modern browser (Chrome, Firefox, Safari, Edge). No server required.

---

## Data Sources

- **Agricultural Statistics United Kingdom 1983** — Ministry of Agriculture, Fisheries and Food (MAFF) / Department of Agriculture and Fisheries for Scotland. All yield, area and livestock projections are derived from this source.
- **Subterranea Britannica** — "Struggle for Survival" (subterranea.org.uk). Strategic fuel stocks and emergency planning data.
- **War Plan UK** (1982) — Duncan Campbell. British government contingency plans. Used with reservations regarding the author's framing.
- **INDEXMUNDI** — UK oil production and consumption 1983–1984 (daily consumption: 1–1.5M barrels/day; production: ~2M b/d).
- **NUKEMAP** — Radioactive fallout modelling. Target set based on Exercise Square Leg (1980). Acknowledged as a simplified model.
- **Agriculture and Horticulture Development Board** — UK wheat and barley distribution maps.

---

## Methodological Note

The analytical method borrows from textual exegesis and applied geography: the film is treated as a text to be interrogated for internal consistency, rather than accepted as authoritative. The author explicitly acknowledges the limitations of the quantitative estimates: consumption ratios are order-of-magnitude calculations designed to constrain the model, not precise simulations. Soil contamination from radioactive fallout is a poorly-quantified parameter and is not modelled in detail.

The comparison with post-Chernobyl Belarus and Ukraine is used specifically to challenge the assumption that radioactive contamination implies agricultural abandonment. Belarus became the world's 8th largest potato producer despite contamination of ~23% of its territory; Ukraine remains the 3rd. The choice between managing contamination risk and accepting 100% famine mortality is not a difficult one.

---

## Author

**Simon Chabrol** — Originally published in English on Reddit and Medium (2025). French translation integrated into the dashboard.

---

---

---

# Threads (1984) — Royaume-Uni post-nucléaire : analyse géo-agricole

> **Un examen critique et quantifié du film BBC *Threads* (1984) sous l'angle de la géographie agricole, de la résilience institutionnelle et de la gouvernance post-effondrement.**

---

## Présentation

Ce projet est un tableau de bord HTML interactif accompagnant une trilogie d'articles analytiques sur le film de la BBC *Threads* (1984), qui met en scène les conséquences d'une attaque nucléaire sur le Royaume-Uni. Plutôt que de traiter le film comme une référence établie sur les conséquences de la guerre nucléaire — ce que font une grande partie de la littérature scientifique, universitaire et journalistique —, ces analyses interrogent sa logique interne : ses prémisses géographiques, ses hypothèses agricoles, ses choix narratifs et les implications éthiques de sa vision du monde.

Le résultat est une inversion du message nihiliste du film. En appliquant les statistiques agricoles, les données géographiques, la logistique pétrolière et les précédents historiques au scénario même du film, l'analyse révèle que les scènes finales de *Threads* — école, hôpital, extraction du charbon, électricité — ne sont pas des anomalies miraculeuses mais le **résultat logiquement inévitable de la géographie agricole britannique**.

Le tableau de bord est un fichier HTML unique et autonome, sans dépendance externe à l'exécution. Il est bilingue (français / anglais) et couvre neuf panneaux analytiques.

---

## Contenu du dépôt

```
threads_v8.html          Tableau de bord interactif principal (autonome, ~900 Ko)
UK_THREADS_book__1_.png  Carte agricole — version française (UK 1985–1997)
UK_THREADS_book__2_.png  Carte agricole — version anglaise (UK 1985–1997)
README.md                Ce fichier
```

---

## Les trois articles

**Article I — UK 1984–1985 : la crise du carburant et l'effondrement sociétal**
Une reconstruction détaillée de la première année suivant l'attaque nucléaire fictive du 26 mai 1984. L'analyse quantifie les stocks stratégiques de carburant du Royaume-Uni (environ 9 millions de barils utilisables au Jour 0, après prise en compte des destructions, des dommages EMP et de l'inaccessibilité), modélise la consommation journalière par phase (générateurs, véhicules militaires, récolte mécanisée) et retrace la cascade d'effondrement jusqu'à sa véritable cause : non pas les bombes, mais le mécanisme de rationnement « travail-contre-nourriture » instauré par les autorités.

**Article II — UK 1985–1994 : le saut narratif inexpliqué**
*Threads* saute dix ans sans explication. Les scènes finales montrent une société structurée — école, hôpital, éclairage public, extraction du charbon, tracteur à vapeur — qui présuppose une agriculture organisée, une gouvernance régionale et une logistique coordonnée. Cet article reconstruit ce qui a nécessairement dû se passer pendant cette décennie, en s'appuyant sur les statistiques agricoles britanniques, la géographie des bassins charbonniers et des analogues historiques (la Révolution des Œillets au Portugal, la dissolution de l'Union soviétique, la fragmentation de l'Empire romain).

**Article III — Réflexions : éthique, dignité humaine, résilience agricole**
Une synthèse des deux articles précédents, examinant la dimension éthique des choix du film : l'inversion par laquelle la résilience est codée comme dégradation, le refus d'imaginer la compétence ou la coordination comme stratégies de survie, et l'incohérence géographique du film (Buxton, dans les tourbières et pâturages du Peak District, est vraisemblablement le pire endroit d'Angleterre pour filmer une reconstitution agricole post-nucléaire).

---

## Panneaux du tableau de bord

| Panneau | Contenu |
|---|---|
| Introduction | Présentation du projet, synopsis de la trilogie, trois questions analytiques centrales |
| Chronologie | Reconstruction chronologique du 26 mai 1984 à 1997, filtrable par phase |
| Données | Graphiques : épuisement du carburant, démographie, cascade de pertes de récolte, rations caloriques, rendements agricoles |
| Carte agricole | Carte interactive bilingue FR/EN avec zoom, déplacement et focus par région |
| États-fragmentaires | Analyse des quatre entités de gouvernance régionale post-effondrement |
| Nouvelle gouvernance | La thèse du « merger » institutionnel : comment fonctionnaires, militaires et experts agricoles ont constitué le noyau de la reconstruction |
| Outils agricoles | Inventaire par phase des outils nécessaires à l'agriculture post-nucléaire, de la moissonneuse-batteuse au moulin à main et à la forge |
| Scénario alternatif | Conséquences quantifiées de l'abandon de l'Est de l'Angleterre (−54 % de surface céréalière, population max. supportable de 2–4 M) |
| Analyse critique | Quatre axes analytiques et réponses aux contre-arguments courants |
| Sources | Sources primaires et transparence méthodologique |

---

## La carte agricole

Les cartes (`UK_THREADS_book__1_.png` en français, `UK_THREADS_book__2_.png` en anglais) sont des productions analytiques originales fondées sur :

- La classification des terres agricoles du Royaume-Uni (données MAFF 1983)
- La distribution des plaines céréalières britanniques
- La géographie des bassins charbonniers britanniques
- Les données de Wytch Farm et des gisements de la Mer du Nord
- L'hypothèse des « États-fragmentaires » (quatre entités régionales : Midlands/Est de l'Angleterre, Écosse centrale, Kent, South-West England)

Les cartes représentent les zones agricoles mécanisées (cercles rouges), les zones d'agriculture manuelle ou à traction animale (cercles blancs), les charbonnages (trame en pointillé), les flux de carburant et de machines (flèches pleines), les flux de bétail (flèches en pointillé) et les deux lignes frontières critiques (ligne Glasgow/Edinburgh ; ligne Newport/Ipswich).

Le tableau de bord intègre les deux images en base64 compressé. La bascule de langue FR/EN dans la barre supérieure permute simultanément le texte de l'interface et la carte.

---

## Notes techniques

Le tableau de bord est un **fichier HTML unique** sans étape de compilation et sans dépendance externe à l'exécution (Chart.js et Google Fonts se chargent depuis un CDN à la première ouverture). Il peut être ouvert directement dans n'importe quel navigateur moderne.

**Fonctionnalités :**
- Bascule de langue FR/EN (tous les textes, images de carte, légendes des graphiques)
- Carte interactive : zoom à la molette, déplacement au clic-glisser, boutons de focus par région
- Filtre de la chronologie par phase (Critique / Transition / Reconstruction / Stabilisation)
- Visualisations de données Chart.js (épuisement du carburant, démographie, cascade de pertes de récolte, rations caloriques, comparaison des rendements)
- Infobulle au survol pour toutes les zones de la carte
- Neuf panneaux navigables via la barre d'onglets

**Compatibilité navigateurs :** Tout navigateur moderne (Chrome, Firefox, Safari, Edge). Aucun serveur requis.

---

## Sources de données

- **Agricultural Statistics United Kingdom 1983** — Ministry of Agriculture, Fisheries and Food (MAFF) / Department of Agriculture and Fisheries for Scotland. Toutes les projections de rendements, surfaces et cheptels en dérivent.
- **Subterranea Britannica** — « Struggle for Survival » (subterranea.org.uk). Données sur les stocks stratégiques de carburant et la planification d'urgence.
- **War Plan UK** (1982) — Duncan Campbell. Plans de contingence du gouvernement britannique. Utilisé avec des réserves sur le cadrage de l'auteur.
- **INDEXMUNDI** — Production et consommation pétrolières du Royaume-Uni 1983–1984 (consommation journalière : 1–1,5 M barils/jour ; production : ~2 M b/j).
- **NUKEMAP** — Modélisation des retombées radioactives. Cibles issues de l'exercice Square Leg (1980). Reconnu comme modèle simplifié.
- **Agriculture and Horticulture Development Board** — Cartes de distribution du blé et de l'orge au Royaume-Uni.

---

## Note méthodologique

La méthode analytique emprunte à l'exégèse textuelle et à la géographie appliquée : le film est traité comme un texte à interroger pour sa cohérence interne, et non comme une autorité à accepter. L'auteur reconnaît explicitement les limites des estimations quantitatives : les ratios de consommation sont des calculs d'ordre de grandeur destinés à contraindre le modèle, non des simulations précises. La contamination radioactive des sols est un paramètre mal quantifié et n'est pas modélisée en détail.

La comparaison avec la Biélorussie et l'Ukraine post-Tchernobyl est utilisée spécifiquement pour remettre en question l'hypothèse selon laquelle la contamination radioactive implique l'abandon agricole. La Biélorussie est devenue le 8e producteur mondial de pommes de terre malgré la contamination d'environ 23 % de son territoire ; l'Ukraine reste le 3e. Le choix entre gérer le risque de contamination et accepter une mortalité de 100 % par famine ne souffre guère d'ambiguïté.

---

## Auteur

**Simon Chabrol** — Publié initialement en anglais sur Reddit et Medium (2025). Traduction française intégrée au tableau de bord.
