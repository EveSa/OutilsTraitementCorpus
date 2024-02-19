---
layout: presentation
title: Cours1
---
# Outils de Traitement de Corpus
👩Eve Sauvage👩

📫eve.sauvage at lisn dot fr📪

🌐[EveSa.github.io/OutilsTraitementCorpus](EveSa.github.io/OutilsTraitementCorpus)🌐

-vertical-
## Organisation du Cours

⏱6 x 3 heures⏱

🏫en salle pouet🏫

-vertical-
## Evaluation

:octocat:

-horizontal-
# Cours 1
## 

-vertical-
### 📄📚Qu'est ce qu'un corpus📚📄
<!--normalement vous savez ce que c'est-->
```js[1|1-2|3]
Une collection de documents
Sur un thème particulier
Pour une tâche particulière
```
---
Avant de revenir sur ces caractéristiques

-vertical-
### A quoi ça sert les data ?
Pour l'apprentissage
- à partir des données/observations, on peut déterminer des paramètres/features qui vont nous permettre de prédire le futur
&rarr; ⛅Prévoir la météo⛅:
    - la saison
    - la couverture nuageuse
    - le vent
    - la météo des régions voisines
    - ...

-vertical-

🤖Pour les machines, c'est pareil !🤖

On a besoin de données pour apprendre les paramètres qui permettent de prédire le futur

&rarr; On collecte des datasets

C'est comme ça qu'on obtient des modèles **prédictifs**

-vertical-

### Une collection = un nombre représentatif de données

**Pour couvrir suffisemment de cas**

⛅Prévoir la météo⛅

- nuage :cloud: = pluie :rain:
- vent :wind: = beau temps :sun:
- nuage :cloud: + vent :wind: = :question:

-vertical-

### Un thème

**Pour éviter le bruit**

⛅Prévoir la météo⛅

- mon humeur de ce matin
- le nombre de café que j'ai bu
- les traces de bouctins devant chez moi
- ...

-vertical-

### Pour une tâche donnée
| | |   
|:---:|:---:|
| Selon la saison | Selon la saison |
| la couverture nuageuse |  la couverture nuageuse |
| le vent | le vent |
| la météo des régions voisines | la météo des régions voisines |
|&rarr; |&rarr; |
|⛅Prédire la météo⛅|🦜Parler de la pluie et du beau temps🦜|

-vertical-
### A quel point c'est important ❓
<!-- Pourquoi on vous parle de corpus tout le temps ?
    Corpus Parallèle et Comparable / Outils de traitement de corpus / Enrichissement de corpus / ...
-->
:heart: C'est le nerf de la guerre :heart:

Les entreprises publient:
- les architectures
- les poids
- mais pas les data ❗

-vertical-

### Les problématiques des data
- Pour les données confidentielles : le RGPD
    - particulièrement visible dans le domaine médical
    &rarr; alors que les modèles sont très bons pour prédire les pathologies
- La propreté des données
    - quand on crawl les data sur internet on a de tout

