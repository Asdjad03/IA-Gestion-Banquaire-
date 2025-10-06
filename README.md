# IA-Gestion-Banquaire-

# Objectif du projet
Ce projet a été réalisé dans le cadre de la 4e année d’ingénierie (EI 2024/2025).
L’objectif est de développer une intelligence artificielle capable d’analyser et de catégoriser automatiquement les dépenses bancaires à partir de relevés de comptes, afin d’aider les utilisateurs à mieux gérer leur budget mensuel.
Ce projet est né d’un constat simple : pour de nombreux étudiants et jeunes actifs, suivre ses dépenses et identifier les postes de coûts importants peut être difficile.
Notre solution apporte une aide concrète en automatisant la catégorisation et la visualisation des transactions.

# Description du projet
1.Extraction & Préparation des données
- Lecture de relevés bancaires au format PDF via Camelot.
- Nettoyage et transformation en CSV avec Pandas.
- Ajout de la colonne catégorie et enrichissement du dataset pour équilibrer les classes.

2.Modélisation et Entraînement
- Utilisation du modèle DistilBERT (version allégée de BERT) pour le traitement automatique du langage (NLP).
- Entraînement sur Google Colab avec un split train (80%) / test (20%).
- Suivi des courbes de loss et d’accuracy sur plusieurs epochs.
- Early stopping pour éviter le surapprentissage.
- Sauvegarde du modèle optimal après évaluation.

3.Interface utilisateur
- Interface Python pour importer un relevé (PDF ou CSV).
- Classification automatique de chaque transaction.
- Visualisation graphique du budget par catégorie.

# Résultats et perspectives
Le modèle a obtenu une bonne précision globale malgré un volume de données limité.
Avec davantage de données, le système pourrait fournir :
- des conseils budgétaires personnalisés,
- des alertes sur les dépassements de dépenses,
- et un suivi mensuel intelligent des habitudes de consommation.

# Compétences mobilisées
- Langages & bibliothèques : Python, Pandas, Camelot, Transformers, Matplotlib
- IA & NLP : DistilBERT, Data cleaning, Tokenization, Fine-tuning
- Outils : Google Colab, GitHub, Google Drive
- Gestion de projet : coordination d’équipe, suivi des tâches, documentation

Modèle entraîné (Drive) :  https://drive.google.com/drive/folders/1xPtaMKAaDghQwQhVIzCSsm-7Vs-RK6Mk?usp=drive_link

# Équipe
Chef de projet : Asdjad BAKARY
Membres : Ilias AMSAL, Ndeye Fatou GAYE, Wassim GHACHI
Encadrants : Arthur Bénard & Nizar Ouarti

