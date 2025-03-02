# PFE - RAG pour la Recherche d'Information en Langue Arabe

Ce projet vise à développer un système de Retrieval-Augmented Generation (RAG) pour la recherche d'information en arabe, une langue à faibles ressources. Le projet se compose de plusieurs étapes : Web Scraping avec Google Search API, Retrieval et Fine-tuning avec QLoRA.

## 📌 Objectifs du projet
- Construire un corpus de données en arabe via Web Scraping avec Google Search API.
- Mettre en place un système de retrieval efficace.
- Affiner un modèle de génération de texte avec QLoRA pour améliorer les réponses.

## 🏗️ Structure du projet

1. **Web Scraping avec Google Search API** :
   - Utilisation de l'API de Google Search pour récupérer des articles et documents en arabe.
   - Extraction et nettoyage des données collectées.

2. **Retrieval** :
   - Indexation des documents collectés.
   - Mise en place d'un système de recherche basé sur les embeddings.

3. **Fine-tuning avec QLoRA** :
   - Ajustement d'un modèle LLM pour améliorer la compréhension et la génération des réponses en arabe.

## 🚀 Installation et Utilisation

### Prérequis
- Python 3.8+
- Pytorch
- LangChain
- QLoRA
- Google Search API

### Installation
```bash
# Cloner le dépôt
git clone https://github.com/bytegajja/PFE-RAG_LANGUAGE-ARAB-
cd PFE-RAG_LANGUAGE-ARAB-

# Installer les dépendances
pip install -r requirements.txt
```

### Utilisation
1. Exécuter le script de Web Scraping avec Google Search API :
   ```bash
   python web_scraper_google.py
   ```
2. Lancer l'indexation des documents :
   ```bash
   python retriever.py
   ```
3. Fine-tuner le modèle avec QLoRA :
   ```bash
   python finetune_qora.py
   ```

## 📜 Licence
Ce projet est sous licence MIT.

## 🤝 Contribuer
Les contributions sont les bienvenues ! Merci de soumettre une PR ou d'ouvrir une issue pour toute suggestion.




