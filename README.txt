#README : Modèles Extractif et Abstrait

Ce projet implémente et compare deux approches de résumé automatique : **extractif** et **abstrait**. L'objectif est d'évaluer leurs performances sur le jeu de données *CNN/Daily Mail* et un jeu de données externe (*SAMSum*).

---

## **Structure du Projet**

### **Données**

Les jeux de données utilisés :
1. *CNN/Daily Mail* :
   - Divisé en ensembles d'entraînement, validation et test.
   - Format : texte source et résumé cible.

2. *SAMSum* :
   - Données de dialogues, utilisées pour tester la généralisation.
   - Fichiers : `samsum-train.csv`, `samsum-test.csv`, `samsum-validation.csv`.

---

## **Installation**

1. Clonez le dépôt GitHub :
   ```bash
   git clone <URL_DU_DEPOT>
   cd <NOM_DU_DEPOT>


2.Installez les dépendances nécessaires :

pip install -r requirements.txt

Principales bibliothèques :

transformers
datasets
nltk
torch


Étape 1 : Prétraitement des données

Exécutez le script de prétraitement :

Étape 2 : Entraînement des modèles

Modèle extractif :

Modèle abstrait :

Étape 3 : Évaluation
Pour évaluer les modèles sur les jeux de test :


Résultats

Performances sur CNN/Daily Mail

Modèle	ROUGE-1	ROUGE-2	ROUGE-L	BLEU
Extractif	0.3338	0.0787	0.2516	2.6523
Abstrait	0.3838	0.1733	0.2636	2.6523

Performances sur SAMSum
ROUGE-1	ROUGE-2	ROUGE-L	BLEU
0.0847	0.0000	0.0595	2.6523

Améliorations Futures

Enrichir les jeux de données avec des textes diversifiés.
Intégrer des contraintes pour les modèles abstraits.
Tester des combinaisons entre approches extractives et abstraites.

Auteurs
- KOANDA Boubacar
- BARRO Ali




