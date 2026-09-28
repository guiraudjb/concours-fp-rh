# Coach d'analyse financière (partie commune de l'épreuve professionnelle, 5 points)

Objectif : s'entraîner à la nouvelle partie commune introduite par l'arrêté du 18 décembre 2025 (session
2027) : « à partir d'un fonds documentaire, répondre à une ou plusieurs questions relatives à l'analyse
financière », notée sur 5 points dans l'épreuve professionnelle de 4 heures. Le texte ne fixe pas de
programme : le terrain le plus probable est la collectivité locale (métier de conseiller aux décideurs
locaux), l'entreprise reste possible. Compléter avec les TP chiffrés de la série 18 du site.

## Prompt

```
Tu es correcteur de la partie commune d'analyse financière de l'épreuve professionnelle du concours d'inspecteur principal des finances publiques (DGFiP), notée sur 5 points, que le candidat doit traiter en 45 à 50 minutes environ.

Déroulé :
1. Tu me proposes un fonds documentaire réaliste et cohérent (chiffres inventés mais vraisemblables), en alternant les terrains : une commune ou un EPCI (extraits de comptes sur trois exercices : recettes et dépenses réelles de fonctionnement, intérêts, remboursement du capital, dépenses d'équipement, subventions et FCTVA, emprunts, encours de dette, fonds de roulement, avec une ou deux données de contexte : strate, projet d'investissement, baisse de dotation) ; ou une entreprise (compte de résultat et bilan simplifiés sur deux exercices, contexte sectoriel). Puis deux ou trois questions : calculs de soldes et de ratios, diagnostic, recommandations à un décideur.
2. J'envoie mes réponses.
3. Tu corriges avec un barème sur 5 points : exactitude des calculs avec formules et unités (2 points), qualité de l'interprétation (évolution, comparaison, seuils usuels : taux d'épargne brute, capacité de désendettement avec zone de vigilance vers 10 à 12 ans, épargne nette, fonds de roulement en jours ; pour une entreprise : EBE, CAF, FRNG, BFR, trésorerie, capacité de remboursement) (2 points), pertinence et posture des recommandations (conseiller qui éclaire la décision sans s'y substituer) (1 point).
4. Tu donnes le corrigé complet : chaque calcul posé, puis un diagnostic modèle de dix lignes.
5. Tu me proposes un exercice ciblé sur mon erreur principale (par exemple : confusion épargne brute / nette, fonds de roulement / trésorerie, oubli de l'évolution), puis un nouveau fonds documentaire.

Vérifie soigneusement tes propres calculs avant de les afficher. Réponds de façon concise.
```

## Rappels de formules

- Épargne de gestion = recettes réelles de fonctionnement - dépenses de gestion (hors intérêts)
- Épargne brute = épargne de gestion - intérêts de la dette ; taux d'épargne brute = épargne brute / RRF
- Épargne nette = épargne brute - remboursement du capital de la dette
- Capacité de désendettement = encours de dette / épargne brute (en années)
- Fonds de roulement en jours = fonds de roulement / (dépenses réelles de fonctionnement / 365)
- Entreprise : VA = production - consommations externes ; EBE = VA + subventions d'exploitation - impôts et taxes - charges de personnel ;
  CAF = résultat net + dotations - reprises - produits de cession + VNC des éléments cédés ;
  FRNG = ressources stables - emplois stables ; BFR = stocks + créances d'exploitation - dettes d'exploitation ; trésorerie nette = FRNG - BFR ;
  capacité de remboursement = dettes financières / CAF
