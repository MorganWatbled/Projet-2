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
- Données brutes des clients affiliés fournies par Pauline (trame Excel) : historique agrégé mensuel de septembre à février par catégorie (feuille *Tableau de bord*), et détail transactionnel de février au niveau client (660 lignes : ID client, temps d'achat, montant, catégorie — feuille *DATA Février*).

**Qualité :**
- Les données sont disponibles à deux granularités cohérentes entre elles : agrégée mensuelle (6 mois, sept.-fév.) et transaction par transaction pour février, ce qui permet de croiser les deux niveaux de lecture.
- Les graphiques fournis par Frédéric sont pré-calculés : l'analyse repose donc sur une confiance dans la fiabilité du script de génération, sans accès direct aux données sources pour ce livrable.

**Limites :**
- Absence de recul historique au-delà de septembre (limite pour la projection du CA à long terme).
- Le changement de stratégie (arrêt du High-Tech) introduit une rupture dans les séries temporelles : les ventes High Tech ne s'arrêtent pas nettement mais déclinent progressivement (3 002 € en septembre → 2 713 € en janvier) avant de tomber à 0 € en février — un point à mentionner pour éviter de lire cette catégorie comme un arrêt franc et immédiat.
- Le fichier clients affiliés ne couvre que le mois de février au niveau transactionnel ; les mois précédents ne sont connus qu'en agrégé, ce qui limite l'analyse de tendance par client.

## Démarche (choix, outils, étapes)

**Volet 1 — Présentation des chiffres clés (destinée à Frédéric)**
1. Sélection, parmi les graphiques générés, des visuels les plus pertinents pour répondre à chaque point demandé (ventes par catégorie, panier moyen, évolutions, temps passé, projection).
2. Structuration en 5 diapositives maximum, un graphique par diapositive, pour respecter la contrainte de concision.
3. Rédaction d'un discours orienté storytelling, vulgarisé pour un public non-data : partir du constat (baisse du CA High Tech compensée par la nourriture), expliquer les causes probables, puis dérouler vers la projection et la recommandation stratégique.
4. Formulation d'une suggestion d'axe stratégique s'appuyant sur le recentrage nourriture / biens de consommation.

**Outil :** PowerPoint.

**Volet 2 — Tableau de bord clients affiliés (destiné à Pauline)**
1. Complétion des données chiffrées du mois de février dans la trame existante.
2. Mise à jour des temps d'achat.
3. Création de 4 graphiques dans la feuille tableau de bord, et mise à jour du premier graphique avec les données de février.
4. Ajout d'une infographie, pour un total de 5 visuels différents dans le tableau de bord.
5. Construction, en feuille 2 (*Tableau Client x Catégorie*), d'un tableau de synthèse par client (nombre d'achats, chiffre d'affaires par catégorie, total).
6. Conservation des formules déjà en place dans le fichier (calcul dynamique, pas de valeurs figées), pour que Pauline puisse se les approprier ultérieurement.
7. Application des bonnes pratiques d'accessibilité (contrastes, lisibilité des libellés, alternatives textuelles) sur l'ensemble des graphiques et du tableau de bord.

**Outil :** Excel.

## Résultats + impact / recommandations

**Chiffre d'affaires (septembre à février, 3 catégories) :**
- CA total cumulé : **204 746,72 €**
- Répartition : nourriture 107 400,82 € (~52 %), biens de conso. 79 290,90 € (~39 %), high tech 18 055,00 € (~9 %, en fin de vie)
- Février est le meilleur mois de la période (39 662,72 €), tiré par la nourriture (24 898,82 €, en forte hausse par rapport à janvier)
- Arrêt du segment High Tech, concentration sur la nourriture : les ventes High Tech déclinent régulièrement (3 002 € en septembre → 0 € en février), tandis que la nourriture est en constante augmentation sur toute la période
- Continuer sur la nourriture : c'est le principal moteur de croissance et de compensation de la perte High Tech
- Biens de consommation : chiffre d'affaires globalement stagnant sur la période — axe identifié : mise en avant produits et offres promotionnelles

**Lien temps passé / panier moyen (données transactionnelles de février) :** les sessions de moins de 4 minutes affichent un panier moyen d'environ 33 € (47 transactions, 1 562,73 €), contre environ 83 € pour les sessions de plus de 9 min 30 (91 transactions, 7 577,32 €) — soit un panier 2,5 fois plus élevé, confirmant que plus le temps passé sur le site est long, plus le panier est grand.

**Axe stratégique proposé à la direction :** segmenter les utilisateurs (le temps passé sur le site étant très hétérogène), simplifier le parcours d'achat et personnaliser les recommandations, pour transformer davantage de visites courtes en sessions longues à panier élevé — en complément d'une mise en avant ciblée des biens de consommation pour sortir de la stagnation.

**Livrables produits :**
- Une présentation de 5 diapositives livrée à Frédéric, couvrant l'ensemble des points demandés : répartition des ventes, panier moyen, évolutions du CA et du trafic, temps passé sur le site, et projection du CA sur les prochains mois.
- Un tableau de bord Excel actualisé pour Pauline, avec 5 graphiques (dont une infographie), un tableau de synthèse par client (dont les clients n°24, 25 et 26 ressortent comme les plus contributeurs sur février, avec un CA individuel dépassant 1 300 €), les formules conservées et documentées pour être réutilisées en autonomie.
- **Impact attendu :** une aide à la décision pour la direction lors de la présentation de fin de semaine, et un outil de suivi pérenne et autonome pour le pôle Marketing sur le segment des clients affiliés.

## Limites + prochaines pistes

- L'analyse s'appuie sur des graphiques déjà générés plutôt que sur les données brutes, ce qui limite la possibilité d'explorer des hypothèses non prévues par le script initial.
- La projection du chiffre d'affaires reste une estimation à horizon court terme, sensible aux aléas externes (saisonnalité, actions promotionnelles non anticipées).
- Le lien entre temps passé et panier moyen n'est établi que sur février : il conviendra de vérifier s'il se confirme sur les mois suivants avant d'en faire un axe stratégique définitif.
- Le tableau de bord clients affiliés est mis à jour manuellement chaque mois : une piste d'amélioration serait d'automatiser la génération des graphiques et du tableau de synthèse à partir des données brutes (macro, requête Power Query, ou script Python).

---

*Projet réalisé dans le cadre de la mission Data Analyst au sein du pôle Marketing du Grand Marché.*
