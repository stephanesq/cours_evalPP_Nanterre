# Inférence causale et évaluation d'impact par différences-en-différences : Applications en *Law and Economics*

## 📚 Contexte

### 🎯 Objectifs pédagogiques

*   Comprendre les fondements de l'inférence causale, en particulier dans le contexte des politiques publiques.
*   **Maîtriser la méthode des différences-en-différences (DiD) comme un outil d'évaluation empirique**.
*   Être capable d'identifier les situations où la DiD est appropriée et de l'appliquer à des questions concrètes en *law and economics*.
*   Savoir interpréter les résultats d'une analyse DiD et évaluer leur robustesse.
*   Être conscient des limites de la méthode et des alternatives possibles.

### **Public cible** : 

Étudiants de Master 2 en économie et droit, ayant des bases en économétrie et en RCT.

### **Durée** : 3 heures

## Structure du cours** :

1.  **Introduction : Pourquoi s'intéresser à l'inférence causale ? (30 minutes)**
    *   Rappel : **Corrélation n'est pas causalité**. Les pièges des analyses naïves.
    *   L'importance de l'évaluation rigoureuse des politiques publiques.
    *   Présentation du **cadre de Rubin** (résultats potentiels, effet du traitement, etc.).
    *   Introduction aux différentes méthodes d'évaluation (expériences, quasi-expériences), et positionnement de la DiD.
    *   Pourquoi la DiD ? Simplicité, pertinence pour les politiques publiques.
2.  **La méthode des différences-en-différences (1h)**
    *   **Principe de base** :
        *   Comparer l'évolution d'un groupe *traité* (soumis à une intervention) avec un groupe *contrôle* (non soumis).
        *   Éliminer les biais liés aux différences préexistantes et aux évolutions temporelles.
    *   **Hypothèses fondamentales** :
        *   **Tendances parallèles** : en l'absence de traitement, les deux groupes auraient suivi des tendances d'évolution similaires.
        *   **L'absence d'effets externes** (SUTVA) : le traitement n'affecte pas le groupe de contrôle.
        *   Comment évaluer la plausibilité de ces hypothèses ?
    *   **Mise en œuvre de la DiD** :
        *   Identifier les groupes et la période d'intervention.
        *   Les données nécessaires (avant/après, groupe traité/contrôle).
        *   **Illustration graphique** : visualisation des tendances et de l'effet du traitement.
    *   **Formulation mathématique** (pour ceux qui souhaitent approfondir) :
        *   L'équation de base de la DiD.
        *   L'estimateur de la DiD.
3.  **Applications pratiques en *law and economics* (1h)**
    *   **Étude de cas 1** : **L'impact d'une loi sur les permis de port d'armes sur la criminalité**.
        *   Groupe traité : États ayant adopté la loi.
        *   Groupe contrôle : États n'ayant pas adopté la loi.
        *   Évolution de la criminalité avant et après l'adoption de la loi.
        *   Analyse des tendances parallèles et des biais potentiels.
    *   **Étude de cas 2** : **L'effet d'une réforme du droit du travail sur l'emploi**.
        *   Entreprises ou secteurs affectés vs non affectés.
        *   L'emploi comme variable d'intérêt.
        *   Interprétation des résultats.
    *   **Étude de cas 3** : **L'impact d'une réforme du système de santé sur l'accès aux soins**.
        *   Régions affectées vs non affectées.
        *   Le recours aux soins comme variable d'intérêt.
        *   Discussion sur la validité de la DiD.
    *   **Étude de cas 4 : l'impact des lois sur l'avortement sur la criminalité**
    *  **Discussion** :
        *  Comment évaluer la crédibilité des résultats ?.
        *  Les **limites** de la méthode DiD.
        *   **Comment identifier un bon groupe de contrôle**?.
        *   Comment gérer les effets de groupe et d'auto-corrélation.
4.  **Conclusion et ouverture (30 minutes)**
    *   **Points clés** : ce qu'il faut retenir de la DiD.
    *   **Ouverture sur les méthodes avancées** :
        *   **DiD avec timing variable** de traitement.
        *   Contrôle synthétique.
        *   Variables instrumentales (une autre approche pour l'inférence causale).
        *   Régression sur discontinuité.
        *   Matching.
    *   L'importance de la rigueur et de la critique dans l'évaluation d'impact.

**Supports de cours** :

*   Slides concis, avec des graphiques et des exemples clairs.
*   Jeux de données (simulés ou réels) adaptés aux cas présentés (un exemple ici :).
*   Articles de référence pour aller plus loin (par exemple,).
*   Code R ou Stata pour la mise en pratique de la DiD.

**Pédagogie** :

*   **Privilégier l'interaction** et les questions.
*   **Mettre l'accent sur l'intuition** et la logique des méthodes plutôt que sur des détails techniques.
*   Faire le lien entre la théorie et la pratique.
*   **Encourager l'esprit critique** et la discussion sur les limites des analyses.

**Points clés pour l'accessibilité et la clarté** :

*   **Langage simple et précis** : éviter le jargon technique inutile.
*   **Exemples concrets et visuels** : utiliser des graphiques et des illustrations pour faciliter la compréhension.
*   **Structurer le cours** : une introduction claire, une partie méthodologique concise, et une large partie consacrée aux applications.
*  **Des cas tirés du *law and economics* qui peuvent être très motivant pour les étudiants.**
*   **Mettre en avant les limites** : être honnête sur les hypothèses et les biais potentiels, et ne pas présenter la DiD comme une solution miracle.

Ce plan de cours devrait permettre aux étudiants de bien comprendre la méthode des différences-en-différences, de l'appliquer à des questions pertinentes en *law and economics*, et de développer leur esprit critique face aux analyses d'impact. N'hésitez pas si vous avez d'autres questions ou si vous souhaitez affiner certains aspects.
