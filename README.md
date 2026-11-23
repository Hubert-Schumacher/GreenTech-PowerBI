# GreenTech – Étude de l’impact des bus électriques aux États-Unis

## Présentation du projet

Ce projet académique réalisé sous **Power BI** porte sur l’adoption des bus scolaires électriques aux États-Unis.

L’objectif était d’exploiter plusieurs jeux de données afin de comprendre comment la transition vers les bus électriques se développe selon les États et les districts scolaires, puis d’étudier ses dimensions **écologiques, sociales et opérationnelles**.

Le projet ne se limite pas à mesurer le nombre de bus électriques. Nous avons également cherché à comprendre quels territoires bénéficient le plus de cette transition, comment les projets évoluent dans le temps et quels facteurs peuvent être associés à leur adoption.

---

## Objectifs

Le rapport répond principalement aux questions suivantes :

- Comment l’adoption des bus électriques évolue-t-elle aux États-Unis ?
- Quels États et districts sont les plus avancés dans cette transition ?
- Comment les projets passent-ils des phases d’attribution à la mise en circulation ?
- Quelles sont les principales sources de financement ?
- Comment l’adoption des bus électriques se répartit-elle selon les caractéristiques socio-économiques des territoires ?
- Existe-t-il des écarts d’adoption entre les districts selon leur niveau de revenu ou leur taux de pauvreté ?
- Comment mettre en relation la transition électrique avec des indicateurs environnementaux tels que les **PM2.5** et l’**ozone** ?

---

## Préparation et modélisation des données

Avant la création des visualisations, nous avons préparé et restructuré les données afin d’obtenir un modèle plus adapté à l’analyse dans Power BI.

Nous avons notamment cherché à nous rapprocher d’un **modèle en étoile**, en distinguant les données servant aux analyses des informations descriptives utilisées pour filtrer et contextualiser les résultats.

Le modèle s’appuie notamment sur des tables relatives :

- aux bus et à leur statut d’adoption ;
- aux districts scolaires ;
- aux États ;
- aux données démographiques ;
- aux indicateurs environnementaux ;
- aux types de carburant ;
- aux sources de financement.

Cette organisation permet de limiter les traitements directement dans les visualisations et de faciliter les analyses à plusieurs niveaux de granularité : **État, district et bus**.

---

## Structure du rapport Power BI

Le rapport est organisé autour de plusieurs pages thématiques.

### 1. Adoption des bus électriques

Cette partie présente une vue globale de l’adoption des bus électriques aux États-Unis.

Elle permet notamment de suivre :

- le nombre d’États et de districts concernés ;
- la part des bus électriques dans le parc étudié ;
- la répartition des bus selon leur statut ;
- l’évolution de l’adoption dans le temps.

### 2. Adoption par État et district

Cette page permet d’identifier les territoires où l’adoption est la plus importante et de comparer les États et districts entre eux.

L’analyse met notamment en évidence une forte concentration des bus électriques dans certains territoires, avec une adoption particulièrement importante en Californie.

### 3. Transition des districts

Cette partie analyse le processus de transition des projets de bus électriques.

Le rapport permet de suivre les différentes étapes :

**Awarded → Ordered → Delivered → Operating**

Nous avons également analysé :

- les délais moyens entre les différentes étapes ;
- les principales sources de financement ;
- les principaux fournisseurs ;
- l’évolution des projets dans le temps.

---

## Analyse de l’impact écologique

Une partie du rapport est consacrée à la dimension environnementale.

Nous avons comparé la présence des bus électriques avec plusieurs informations liées au parc de véhicules et à la pollution, notamment :

- les différents types de carburant ;
- la concentration en **PM2.5** ;
- la concentration en **ozone** ;
- la répartition des bus diesel et électriques selon différents niveaux de pollution.

L’objectif était d’explorer la manière dont la transition vers l’électrique s’inscrit dans des territoires présentant des situations environnementales différentes.

Ces analyses permettent d’étudier les liens entre mobilité scolaire, électrification du parc et enjeux environnementaux, sans pour autant conclure à une relation de causalité directe entre l’adoption des bus électriques et le niveau de pollution.

---

## Analyse de l’impact social

Nous avons également étudié la dimension sociale de la transition.

Pour cela, nous avons croisé les données d’adoption des bus électriques avec plusieurs indicateurs socio-économiques, notamment :

- le revenu médian des districts ;
- le pourcentage de population vivant sous le seuil de pauvreté ;
- le type d’environnement du district : urbain, suburbain, rural ou town.

### Principale conclusion

Notre analyse suggère que les territoires disposant de revenus plus élevés sont davantage représentés dans l’adoption des bus électriques.

À l’inverse, les districts présentant des taux de pauvreté plus élevés semblent moins bénéficier de cette transition.

Nous avons donc identifié un **enjeu d’équité dans la transition écologique** : l’accès aux nouvelles solutions de mobilité électrique ne semble pas se répartir de manière homogène entre les territoires.

Cette observation correspond à une association visible dans les données analysées et ne permet pas, à elle seule, d’établir une relation de causalité.

---

## Principaux enseignements

Le projet met notamment en évidence que :

- l’adoption des bus électriques reste concentrée dans certains États et districts ;
- la transition s’est fortement accélérée au cours des dernières années de la période étudiée ;
- le financement joue un rôle important dans le déploiement des projets ;
- la transition vers les bus électriques présente des disparités territoriales importantes ;
- les districts les plus favorisés économiquement semblent davantage bénéficier de l’électrification des bus scolaires ;
- l’analyse croisée des données environnementales et sociales permet d’aller au-delà d’un simple suivi du nombre de bus électriques.

---

## Technologies utilisées

- **Power BI Desktop**
- **Power Query**
- **DAX**
- Modélisation de données
- Data visualisation
- Analyse exploratoire de données

---

## Compétences mobilisées

Ce projet nous a permis de travailler sur plusieurs étapes d’un projet Data / BI :

- préparation et structuration des données ;
- modélisation pour l’analyse ;
- création d’indicateurs ;
- conception de tableaux de bord interactifs ;
- analyse de données environnementales et socio-économiques ;
- interprétation et restitution des résultats.

---

## Équipe

Projet réalisé dans le cadre de la formation **Business Intelligence & Analytics – EFREI Paris**.

**Équipe GreenTech :**

Clément LE CORRE - Hubert Schumacher - Stéphanie LI - Kevin OP - Sam PONDEVIE
