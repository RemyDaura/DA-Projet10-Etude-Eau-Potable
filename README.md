# Étude sur l'Accès à l'Eau Potable dans le Monde

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Viz](https://img.shields.io/badge/Data_Viz-Analytics-FF6F61?style=for-the-badge)

## Contexte du Projet
Ce projet a été réalisé dans le cadre de mon parcours de Data Analyst avec OpenClassrooms. L'objectif était de concevoir un tableau de bord analytique et dynamique pour une Organisation Non Gouvernementale (ONG) afin de lui offrir une visibilité globale sur l'accès à l'eau potable à l'échelle internationale. Cet outil décisionnel est conçu pour identifier précisément les zones prioritaires et guider le déploiement des futures missions humanitaires et financements.

**Mission :** Traduire le besoin de l'ONG en questions analytiques, élaborer la structure visuelle (Blueprint & Mock-up), nettoyer les sources de données, et développer un rapport multi-pages interactif facilitant l'exploration géographique et temporelle.

## Architecture Technique
* **Business Intelligence & Data Viz :** Power BI Desktop (Conception des visualisations, modèle de données et indicateurs).
* **ETL (Extract, Transform, Load) :** Power Query pour l'ingestion, le nettoyage, le pivotement et la modélisation des jeux de données.
* **Langage de calcul :** DAX (Data Analysis Expressions) pour la création de mesures calculées et de KPI sur mesure.
* **Contrôle de version :** Git & GitHub.

## Structure du Projet (Modélisation & Pages)
Le projet applique un flux d'ingestion rigoureux suivi d'une architecture de rapport fluide divisée en 3 niveaux d'analyse :

* `Préparation (Power Query)` : Consolidation et normalisation.
  * Traitement des valeurs manquantes, harmonisation des dénominations des pays et création d'une table calendrier pour le suivi temporel.
* `Rapport Power BI (Rapport Multi-pages)` : 
  * **Vue d'ensemble mondiale :** Cartographie interactive et indicateurs clés (taux d'accès global, évolution globale, population touchée).
  * **Analyse comparative :** Classement des pays et régions selon les critères de stress hydrique et d'infrastructures.
  * **Focus pays (Fiche détail) :** Page approfondie permettant d'isoler un pays spécifique pour valider sa pertinence comme cible prioritaire pour l'ONG.

## Conception et Règles de Qualité
La robustesse et l'intuitivité du tableau de bord reposent sur une méthodologie de conception centrée utilisateur :
* **Cadrage du besoin :** Production préalable d'un blueprint et d'un mock-up basse définition pour valider l'expérience utilisateur (UX) avant le développement.
* **Pertinence visuelle :** Sélection stricte des graphiques (cartes de formes, diagrammes en barres segmentées, matrices) en parfaite adéquation avec le type de données représentées.
* **Modèle en étoile :** Organisation optimisée des relations entre la table de faits (données d'accès à l'eau) et les tables de dimensions (géographie, calendrier).

## Résultats
* **89 %** d'accès basique à l'eau dans le monde en 2017, mais seulement **26 %** d'accès à une eau réellement propre (« safely managed ») : un écart de **62,9 points**. Le vrai sujet est la qualité de l'eau, pas l'accès.
* En Afrique subsaharienne, l'accès basique tombe à 62 % et l'accès à une eau de qualité à 7 %.
* Une recommandation par domaine d'intervention de l'ONG : création de services en Afrique subsaharienne rurale, modernisation en Asie du Sud et du Sud-Est, conseil aux gouvernements dans des pays stables à forte mortalité liée à l'eau.
* Accessibilité : texte alternatif sur chacun des 21 visuels et contrastes conformes WCAG.

## Contenu du dépôt
* `reports/` : le fichier Power BI (`.pbix`), la présentation et le blueprint des indicateurs
* `data-raw/` : les sources OMS et Banque mondiale, et le dictionnaire de données
* `images/` : captures d'écran

<img src="images/Capture d'écran 2026-05-04 122245.png" width="500px"><img src="images/Capture d'écran 2026-05-04 122254.png" width="500px">
<img src="images/Capture d'écran 2026-05-04 122305.png" width="500px">

---
📂 Dossier complet sur mon portfolio : [remydaura.github.io/p10.html](https://remydaura.github.io/p10.html)

*Ce projet fait partie de la formation Data Analyst d'OpenClassrooms.*
