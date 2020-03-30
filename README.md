# Covid19Fr
Sous-repository du études réalisées par OpenCovid19FR. Lien vers le repo père [ici](https://github.com/opencovid19-fr).

**Table of Contents**
[TOCM]
[TOC]

## 0.1 TL;DR - Résultats clés

Pour le moment, phase exploratoire / documentation - pas de résultat.

## 0.2 Annonces urgentes


## 1. Roadmap du WP prediction ML
### 1.1. Echéancier
La roadmap du WP Prediction s'articule ainsi:

1. Propagation et pics épidémiques par zone de France 
2. Demande en matériel de soins (lits, matériel de réanimation)
3. Taux d'infectiosité chez le personnel soignant
4. Demande en masques (tous types)

Il dépend du WP1, DataCollection, qui va permettre de créer une pipeline vers les modèles de prédiction considérés. Le repo actuel se concentre sur le point 2. de la roadmap.

### 1.2. Livrables
Plusieurs livrables sont envisagés pour cette étude:
1. Rapport d'étude sur la modélisation de la demande en lit & matériel de réanimation: méthodologie et résultats clés
2. Si le rapport le valide, modèle prédictif (entièrement documenté) mis en production - dans un premier temps non packagé

## 2. Ressources disponibles

Plusieurs ressources sont connexes à ce repo:
1. Document Word partagé (compte-rendu) : ici
2. Channel slack : [nomduchannel]

## 3. Contenu du repo

La repo se compose de plusieurs éléments, à savoir:
+ data input: Donnée en pipeline
  + Données globales sur la propagation du virus / source: OpenCovid19
  + Données sur la capacité en lits d'hôpital / matériel de réanimation par zone / source: (A définir)
  + (Ajouter autres sources de donnée)
+ pred_epid: premier modèle prédictif - modélisation de l'épidémie par un modèle simple 
+ pred_beds: second modèle prédictif - modélisation de la demande en lit et matériel d'hôpital

## 4. Résultats

### 4.1. Prédiction propagation Covid 19
Source : [Kaggle contest](https://www.kaggle.com/c/covid19-global-forecasting-week-1/notebooks?sortBy=hotness&group=everyone&pageSize=20&competitionId=19539)

### 4.2. Prédiction demande lit d'hôpital

## 5. Bibliographie

+ Etude source sur le stress testing de la demande en lits d'hôpitaux / matériel de réanimation: [Article CHU Rouen](https://www.ea-reperes.com/wp-content/uploads/2020/03/PredictedFrenchHospitNeeds-EHESP-20200316.pdf)
+ Etudes réalisées pour la prédiction SEIR du Covid19: [Kaggle contest](https://www.kaggle.com/c/covid19-global-forecasting-week-1/notebooks?sortBy=hotness&group=everyone&pageSize=20&competitionId=19539)
+ Modélisation de la propagation de l'épidémie H1N1: [Article](https://static-content.springer.com/esm/art%3A10.1186%2F1741-7015-7-45/MediaObjects/12916_2009_223_MOESM1_ESM.pdf)
