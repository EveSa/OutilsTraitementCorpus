# 👩 Qui suis-je 👩 

- Eve Sauvage
- ancienne étudiante du master TAL
- doctorante au LISN à l'université Paris-Saclay
- mon sujet : `le traitement des séquences longues avec les modèles d'apprentissage profond`

**Me joindre :** 

- 📫  eve.sauvage at lisn dot fr *avec "outils de traitement de corpus" dans l'objet svp*
- 🌐  <https://EveSa.github.io/OutilsTraitementCorpus>

#  🎓 Présenter le cours 🎓

**Comment ça va ce passer :** 

- 6 séances 
- du 18 mars au 13 mai
- de 15h30 à 18h30
- En salle 308
- partagé en 3 parties : 
  - Une partie cours magistral
    \&rarr; n'hésitez pas à poser des questions
  - Une partie retours 
    - sur le cours
    - préparation du cours d'après (qu'est ce que vous voulez voir la prochaine fois, de quoi vous voudriez entendre parler)
    - un petit point bonnes pratiques
  - Une partie pratique

**Évaluation :** 

On fait un projet de constitution/exploitation de corpus en faisant

Un TP après chaque séance, sauf la première et la dernière, sur Github.
7 séances, 5 TP, 1 projet

Tous vos devoirs devront m’être parvenus avant le 26 mai

# Index des cours

- [Cours 1](/slides/cours1-2024.html)
- Cours 2
  - [slides](/slides/cours2-2025.html)
  - [notebook](/notebooks/web_scrap.ipynb)
- Cours 3
  - [slides](/slides/cours3-2025.html)
  - [notebook](/notebooks/web_scrap.ipynb)
- Cours 4
  - [slides](/slides/cours4-2025.html)
  - [notebook](/notebooks/visualise_data.ipynb)
  - [Dockerfile](/src/dockerssh.zip)
- Cours 5
  - [slides](/slides/cours5.html)
  - [notebook](/notebooks/significativity_test.ipynb)
- Cours 6
  - [slides](/slides/cours6.html)

Accès à la newsletter &rarr; [newsletter](./newsletter.md)

## Déroulé des TP

#### TP 1 :

Partie 1 | étude de cas *CoNLL 2003* :

1. Quelle type de tâche propose CoNLL 2003 ?
2. Quel type de données y a-t-il dans CoNLL 2003 ?
3. A quel besoin répond CoNLL 2003 ?
4. Quels types de modèles ont été entraînés sur CoNLL 2003 ?
5. Est un corpus monolingue ou multilingue ?

Partie 2 | projet:

En vous inspirant des informations que vous avez récupérées pour CoNLL 2003, définissez les besoins de votre projet:
- dans quel besoin vous inscrivez vous ?
- quel sujet allez vous traiter ?
- quel type de tâche allez vous réaliser ?
- quel type de données allez vous exploiter ?
- où allez vous récupérer vos données ?
- sont-elles libres d'accès ?

#### TP 2:

Récuperer votre corpus de travail à partir d'une resource web (pas d'API)

mettez votre script de crawling et de scraping sur votre github en respectant l'arborescence de dossiers présenté au cours 3

#### TP 3:

Visualiser votre corpus et réaliser des statistiques de texte
 
    ex. :
    1. longueur des textes
    2. mots fréquents (zipf)
    3. les statistiques adaptées à votre tâche

#### TP 4 : 

- A partir des données que vous avez récupérées, caugmentez vos données en créant un dataset synthétique.
- Choississez l'architecture adaptée à votre tâche et trouvez un modèle qui correspond à votre tâche et à cette architecture.

#### TP 5

- Finetuner le modèle pretrained qui correspond le plus à vos données grâce au trainer d'hugging face

#### TP 6

- Evaluer votre modèle
