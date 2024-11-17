![Réaliser un dashboard et assurer une veille technique](https://raw.githubusercontent.com/Sengsathit/OCR_data_scientist_assets/main/header_pret_a_depenser.png?raw=true)

# PROJET : Réaliser un dashboard et assurer une veille technique

Nous considérons, pour ce projet, l’entreprise **Prêt à dépenser** qui propose des crédits à la consommation. Après avoir conçu un modèle de scoring crédit pour évaluer la probabilité de remboursement des clients, l’entreprise souhaite renforcer la transparence et l’accessibilité des décisions prises en créant un dashboard interactif destiné aux chargés de relation client.

En parallèle, il est réalisé une veille technique sur les dernières avancées en Data Science, afin d’identifier et tester des techniques innovantes susceptibles d'améliorer les performances des modèles de données texte ou d'image.

## Structure du dépôt

- `1_dashboard` : Ce dossier contient tous les fichiers nécessaires à la mise en œuvre d’un dashboard interactif destiné aux chargés de relation client. Ce dashboard utilise les résultats du modèle de scoring crédit pour fournir une interface intuitive et accessible permettant de visualiser et d’expliquer les décisions prises.
- `2_notebook_veille.ipynb` : Ce notebook documente une veille technique axée sur les Vision Transformers (ViT), accompagnée d’un Proof of Concept (POC) pratique. Ce travail repose sur une comparaison directe des performances des ViT avec celles obtenues dans un projet précédent utilisant VGG16, une architecture classique de Convolutional Neural Networks (CNN).
- `3_note_methodologique` : Ce document formalise la démarche méthodologique suivie pour la veille technique sur les Vision Transformers et leur application à un problème concret.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter les notebooks.

---

## Prérequis

Pour exécuter ce projet, vous aurez besoin de Python (version 3.8 ou supérieure). Il est également recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.

### Étapes pour créer et activer un environnement virtuel :

1. Créez un environnement virtuel :
   ```bash
   python -m venv .venv
   source .venv/bin/activate

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
