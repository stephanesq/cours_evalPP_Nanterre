# Méthodes d'Évaluation des Politiques Publiques

Bienvenue dans le dépôt dédié au cours du M2 Economie du droit sur les **méthodes d'évaluation des politiques publiques**.

## 📚 Contexte

Ce dépôt contient les supports de cours, exercices, et lectures pour un module sur les **méthodes d'évaluation des politiques publiques**. Ce cours est destiné à des étudiants ou professionnels souhaitant approfondir leur compréhension des outils modernes d'évaluation d'impact, avec une emphase sur les méthodes quantitatives et causales.

Les approches couvertes incluent :

-   Expérimentations randomisées (RCT),
-   Régressions avec discontinuités (RDD),
-   Double différence (DiD),
-   Variables instrumentales (IV),
-   Appariement par score de propension (PSM).

Les applications sont inspirées de travaux en *Law and Economics*.

❌ Ce cours n'aborde ni :

-   Les études d'impact (évaluation *ex ante*).

-   La gestion d'un projet d'évaluation.

### 🎯 Objectifs pédagogiques

-   Comprendre les concepts fondamentaux de l'évaluation causale.
-   Savoir appliquer les méthodes appropriées à des contextes empiriques variés.
-   Développer une approche critique face aux résultats d'études empiriques.

------------------------------------------------------------------------

## 🗂️ Structure du dépôt

-   **`/_cours`** : Présentations du cours en format PDF ou PPT.
-   **`/code`** : Scripts R et Python pour illustrer les méthodes.
-   **`/data`** : Jeux de données utilisés dans les travaux pratiques.
-   **`/_exercices`** : Exercices et corrigés (théoriques et pratiques).
-   **`/readings`** : Articles et lectures complémentaires (PDF).

------------------------------------------------------------------------

## 🎓 Syllabus

### 1. Introduction

-   Topics for evaluation
-   Organisation of evaluation around the world and in France
-   Types of evaluation methods
-   Basic Theory of Impact Evaluation

### 2. Randomization

-   Statistical Design of Randomization
-   Field Experiments (method, treatment effects)
-   Different Methods of Randomization
-   Natural and Lab Experiments
-   Limitations

### 3. Propensity Score Matching

-   Setup and assumptions
-   Exact Matching & matching using Propensity Scores
-   Treatment Effects and Selection Bias
-   Application and Limits of the PSM Method

### 4. Double Difference

-   Theory and Application (Two-Period Model, Panel Fixed-Effects Model)
-   Implementation
-   Advantages and Disadvantages
-   Alternative DD Models

### 5. Instrumental Variable Estimation

-   Two-Stage Least Squares (2SLS) Approach
-   Sources of IVs
-   Concerns

### 6. Regression Discontinuity

-   Regression Discontinuity in Theory (Steps in Applying the RD Approach and Variations of RD)
-   Advantages and Disadvantages

------------------------------------------------------------------------

## 🛠️ Configuration requise

1.  **Langages et logiciels** :
    -   R (version ≥ 4.2) avec les packages `dplyr`, `ggplot2`, `data.table`, etc.
    -   Python (version ≥ 3.8) avec `pandas`, `statsmodels`, `matplotlib`.
2.  **Dépendances spécifiques** :
    -   Instructions pour installer les packages nécessaires dans un environnement virtuel.

------------------------------------------------------------------------

## 🔧 Utilisation

1.  Clone le dépôt :

    ``` bash
    git clone https://github.com/username/cours-evaluation.git
    ```

2.  Installe les dépendances :

    ``` bash
    Rscript install_dependencies.R
    pip install -r requirements.txt
    ```

3.  Exécute les notebooks ou les scripts pour explorer les méthodes.

------------------------------------------------------------------------

## 📖 Références et lectures recommandées

1.  **"Angrist, J.D., & Pischke, J.S."** *Mostly Harmless Econometrics* (2009).
2.  Articles scientifiques inclus dans le dossier `/readings`.

------------------------------------------------------------------------

## 🤝 Contribuer

-   Les contributions (scripts, lectures, corrections) sont bienvenues. Crée une pull request ou ouvre une issue pour toute suggestion

------------------------------------------------------------------------

## Ressources

-   Outil interactif <https://mattblackwell.github.io/gov2002-book/>
-   Références en français
    -   [Givord, P. (2014). Méthodes économétriques pour l’évaluation de politiques publiques. Économie & prévision, 204205(1), 1-28.](https://www.insee.fr/fr/statistiques/1380865)
-   Ouvrages en ligne ([🇬🇧](https://emojipedia.org/fr/drapeau-royaumeuni))
    -   [Cunningham, S. (2021). *Causal inference: The mixtape*. Yale university press.](https://mixtape.scunning.com) : traite
    -   [Huntington-Klein, N. (2021). *The effect: An introduction to research design and causality*. Chapman and Hall/CRC.](https://theeffectbook.net/)
