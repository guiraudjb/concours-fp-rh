# Prompts de chatbot pour l'oral (et l'écrit) du concours d'inspecteur principal DGFiP

Chaque fichier contient un prompt prêt à coller dans un chatbot : Le Chat, ChatGPT, Claude, Gemini, ou un
modèle local (Ollama + Open WebUI, par exemple `gemma4:26b`). Copier tout le bloc « Prompt » dans un
**nouveau** fil de discussion, puis répondre à la première question du chatbot.

Les prompts suivent le format du concours **depuis la réforme** (arrêté du 2 mars 2011 modifié, notamment
par l'arrêté du 18 décembre 2025) :

- **Note administrative** sur dossier : 5 heures, coefficient 6 ; elle porte sur l'environnement de la DGFiP
  et sur les politiques publiques dans lesquelles la DGFiP intervient.
- **Épreuve professionnelle** : 4 heures, coefficient 6 ; l'option est notée sur 15 points et une **partie
  commune d'analyse financière** (fonds documentaire, puis questions) sur 5 points, à partir de la session 2027.
- **Oral d'admission unique** : entretien de 40 minutes, coefficient 8, sans préparation ; présentation du
  parcours en 10 minutes au maximum, puis échange comprenant des **mises en situation** qui évaluent le
  savoir-être ; **CV libre transmis en amont**. Il remplace les deux oraux (cas pratique préparé, puis
  entretien) décrits dans les rapports de jury jusqu'en 2025.

Ils reprennent les reproches récurrents des rapports de jury 2019-2026 :
- se positionner en cadre A et non en **inspecteur principal** ;
- présentation descriptive et récitée ;
- réponses convenues ;
- manque d'engagement et de posture ;
- méconnaissance du réseau DGFiP et des réformes en cours.

Ce qui est valorisé : hauteur de vue, propositions opérationnelles et concrètes, réponses argumentées issues
d'une réflexion personnelle, capacité à tenir sa position avec calme.

| Fichier | Usage | Durée conseillée |
|---|---|---|
| [01-jury-oral-entretien.md](01-jury-oral-entretien.md) | Simulation complète de l'entretien de 40 minutes (CV, présentation, mises en situation), note et débrief | 50 min |
| [02-cv-et-presentation-10-minutes.md](02-cv-et-presentation-10-minutes.md) | Rédiger le CV transmis en amont et construire la présentation de 10 minutes | 30 min |
| [03-reflexes-rafale.md](03-reflexes-rafale.md) | Rafales de situations courtes pour automatiser les réflexes de cadre supérieur | 10-15 min / jour |
| [04-banque-mises-en-situation.md](04-banque-mises-en-situation.md) | Génère des mises en situation avec éléments de corrigé (seul ou en binôme) | à la demande |
| [05-mise-en-situation-express.md](05-mise-en-situation-express.md) | Répondre sans préparation en 2 à 3 minutes, avec relance | 20 min |
| [06-questions-destabilisantes.md](06-questions-destabilisantes.md) | Stress test : relances, contradiction, déontologie, loyauté | 15 min |
| [07-connaissance-dgfip.md](07-connaissance-dgfip.md) | Interrogation sur l'organisation, les missions et l'environnement de la DGFiP | 15 min |
| [08-revision-fiche.md](08-revision-fiche.md) | Interrogation progressive à partir d'une fiche du site | 15 min |
| [09-coach-plan-ecrit.md](09-coach-plan-ecrit.md) | Correction de plans de note administrative (complète les TP du site) | 20 min |
| [10-debrief-progression.md](10-debrief-progression.md) | Bilan de plusieurs séances et plan de travail personnalisé | 10 min |
| [11-coach-analyse-financiere.md](11-coach-analyse-financiere.md) | Partie commune d'analyse financière (5 points) : fonds documentaire, calculs, diagnostic | 50 min |

Conseils d'usage :

- **Parler, pas écrire** : utiliser la saisie vocale du chatbot (ou lire sa réponse à voix haute) pour
  l'entretien, les mises en situation et les rafales. Chronométrer soi-même la présentation de 10 minutes.
- **Un thème par séance** : joindre au besoin une fiche du site (bouton Fiche) pour ancrer les questions.
- **Vérifier les faits** : un chatbot peut se tromper sur un chiffre, une date ou une réforme récente.
  Les prompts lui demandent de signaler ses incertitudes, mais les fiches et les sources officielles
  font foi.
- **Ne jamais coller de données personnelles ou internes** (noms d'agents, dossiers fiscaux, documents
  non publics) dans un chatbot en ligne.

## Coach cybersécurité, cyberrésilience et référentiels (prompts 21 à 28)

Série commune à tous les dépôts, liée au module 00-10 (rapport d'incident de l'ANSSI sur les cyberattaques ayant touché la DGFiP, 2026) et aux modules sur les référentiels (RGS, RGI, RGPD, RGESN, RGAA, NIS 2, CRA). Les prompts 24 et 25 reçoivent automatiquement la fiche du module sélectionné dans l'onglet IA. Aucun prompt ne demande de détail technique d'attaque : ils restent au niveau de la prévention, de la décision et de la gouvernance. Ne jamais coller de données personnelles ou internes dans un chatbot en ligne.

| Fichier | Usage | Durée conseillée |
|---|---|---|
| [21-coach-cyber-reflexes.md](21-coach-cyber-reflexes.md) | Rafales de situations du quotidien (messagerie, identifiants, poste, télétravail) pour automatiser les bons réflexes | 10 min / jour |
| [22-simulation-crise-cyber.md](22-simulation-crise-cyber.md) | Exercice de crise cyber avec injects : décisions, notifications (CNIL, NIS 2, ANSSI), communication, débrief | 30-40 min |
| [23-coach-cyberresilience.md](23-coach-cyberresilience.md) | Atelier de cyberrésilience d'un service : anticiper, résister, mode dégradé, reprise, feuille de route | 30 min |
| [24-referentiels-interrogation.md](24-referentiels-interrogation.md) | Interrogation croisée sur RGS, RGI, RGPD, RGESN, RGAA, NIS 2, CRA, DORA, DSA, Data Act et feuille de route de l'État | 20 min |
| [25-analyse-incident-referentiels.md](25-analyse-incident-referentiels.md) | Analyse d'un incident (module 00-10 par exemple) au prisme des référentiels, grille d'écarts et plan de note | 30 min |
| [26-atelier-ebios-homologation.md](26-atelier-ebios-homologation.md) | Les cinq ateliers d'EBIOS Risk Manager puis le dossier d'homologation d'un SI | 45 min |
| [27-jury-cyber-posture.md](27-jury-cyber-posture.md) | Questions de jury sur la cybersécurité vue par un encadrant : arbitrages, responsabilité, management | 20 min |
| [28-sensibiliser-son-equipe.md](28-sensibiliser-son-equipe.md) | Construire et répéter une séquence de sensibilisation de 15 minutes pour son équipe | 30 min |
