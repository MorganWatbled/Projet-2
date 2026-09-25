# Rapport mensuel marketing — Le Grand Marché

Analyse mensuelle des performances marketing (chiffres clés + suivi des clients affiliés) pour une entreprise de grande distribution.

---

## Contexte / besoin métier

Le Grand Marché est une entreprise de grande distribution (nourriture, biens de consommation) qui gère un entrepôt et livre à domicile les commandes passées sur son site Internet. L'entreprise a opéré un changement stratégique l'année précédente en arrêtant le segment High-Tech pour se recentrer sur l'alimentaire et les biens de consommation.

Chaque début de mois, le pôle Marketing produit un rapport présenté en fin de semaine à la direction. Ce projet répond à deux besoins distincts exprimés par deux interlocuteurs :

- **Frédéric, Directeur Marketing** — une présentation synthétique (5 diapositives maximum, 1 graphique par diapositive) expliquant l'évolution du chiffre d'affaires, ses causes, sa projection, et proposant un axe stratégique. Le discours doit être accessible à un public non technique et recourir au storytelling.
- **Pauline, pôle Marketing** — un tableau de bord Excel dédié au suivi des clients affiliés, mis à jour mensuellement (données de février), avec graphiques et vue de synthèse par client, dans le respect des bonnes pratiques d'accessibilité.

L'enjeu métier commun : donner à la direction une lecture claire et actionnable de la performance commerciale et digitale du mois, pour orienter les décisions stratégiques à venir.

## Données (source, qualité, limites)

**Sources :**
- Graphiques mensuels générés automatiquement par un script interne (ventes par catégorie, panier moyen, évolutions du CA, du nombre d'achats, du ratio achats/visites, du nombre de visites, du temps passé sur le site).
- Données brutes des clients affiliés fournies par Pauline (trame Excel), avec le mois de janvier déjà renseigné et les données de février à intégrer.

**Qualité :**
- [À compléter : préciser la fraîcheur des données (date d'extraction), le taux de complétude, et si un contrôle de cohérence a été effectué entre les graphiques générés par script et les données brutes]
- Les graphiques fournis par Frédéric sont pré-calculés : l'analyse repose donc sur une confiance dans la fiabilité du script de génération, sans accès direct aux données sources pour ce livrable.

**Limites :**
- Absence de recul historique au-delà de la période disponible (limite pour la projection du CA).
- Le changement de stratégie (arrêt du High-Tech) introduit une rupture dans les séries temporelles, à isoler pour ne pas biaisser l'analyse des tendances.
- [À compléter : toute donnée manquante, valeur aberrante ou period gap identifié dans le fichier clients affiliés]

## Démarche (choix, outils, étapes)

**Volet 1 — Présentation des chiffres clés (destinée à Frédéric)**
1. Sélection, parmi les graphiques générés, des visuels les plus pertinents pour répondre à chaque point demandé (ventes par catégorie, panier moyen, évolutions, temps passé, projection).
2. Structuration en 5 diapositives maximum, un graphique par diapositive, pour respecter la contrainte de concision.
3. Rédaction d'un discours orienté storytelling, vulgarisé pour un public non-data : partir du constat (baisse du CA), expliquer les causes probables, puis dérouler vers la projection et la recommandation stratégique.
4. Formulation d'une suggestion d'axe stratégique s'appuyant sur le recentrage nourriture / biens de consommation.

**Outil :** PowerPoint.

**Volet 2 — Tableau de bord clients affiliés (destiné à Pauline)**
1. Complétion des données chiffrées du mois de février dans la trame existante.
2. Mise à jour des temps d'achat.
3. Création de 4 graphiques dans la feuille tableau de bord, et mise à jour du premier graphique avec les données de février.
4. Ajout d'une infographie, pour un total de 5 visuels différents dans le tableau de bord.
5. Construction, en feuille 2, d'un tableau de synthèse par client (nombre d'achats, chiffre d'affaires, total).
6. Conservation des formules déjà en place dans le fichier (calcul dynamique, pas de valeurs figées), pour que Pauline puisse se les approprier ultérieurement.
7. Application des bonnes pratiques d'accessibilité (contrastes, lisibilité des libellés, alternatives textuelles) sur l'ensemble des graphiques et du tableau de bord.

**Outil :** Excel.

## Résultats + impact / recommandations

- Une présentation de 5 diapositives livrée à Frédéric, couvrant l'ensemble des points demandés : répartition des ventes, panier moyen, évolutions du CA et du trafic, temps passé sur le site, et projection du CA sur les prochains mois.
- Arrêt du segment high Tech, concentration sur la nourriture.
- Continuer sur la nourriture
- Un tableau de bord Excel actualisé pour Pauline, avec 5 graphiques (dont une infographie), un tableau de synthèse par client, les formules conservées et documentées pour être réutilisées en autonomie.
- **Impact attendu :** une aide à la décision pour la direction lors de la présentation de fin de semaine, et un outil de suivi pérenne et autonome pour le pôle Marketing sur le segment des clients affiliés.

## Limites + prochaines pistes

- L'analyse s'appuie sur des graphiques déjà générés plutôt que sur les données brutes, ce qui limite la possibilité d'explorer des hypothèses non prévues par le script initial.
- La projection du chiffre d'affaires reste une estimation à horizon court terme, sensible aux aléas externes (saisonnalité, actions promotionnelles non anticipées).
- Le tableau de bord clients affiliés est mis à jour manuellement chaque mois : une piste d'amélioration serait d'automatiser la génération des graphiques et du tableau de synthèse à partir des données brutes (macro, requête Power Query, ou script Python).
---

*Projet réalisé dans le cadre de la mission Data Analyst au sein du pôle Marketing du Grand Marché.*
