

# 🏋️‍♂️ Agent IA Fitness — RAG Chatbot

Bienvenue dans le dépôt de mon **Agent IA spécialisé dans le fitness**. Cet agent utilise l'architecture **RAG (Retrieval-Augmented Generation)** pour répondre aux questions sur le sport et la nutrition en se basant *uniquement* sur une base de documents certifiés.

> 🎓 **Contexte** : ce projet a été réalisé pendant l'atelier code de la formation **"Objectif IA"** de [Machine Learnia](https://www.machinelearnia.com/), animée par **Guillaume** (soirée du 03/09/2026). La structure du notebook et la méthode pédagogique (chunking, recherche sémantique, RAG) viennent de cette formation — j'ai suivi l'atelier en direct, complété les exercices, et personnalisé le projet à mon tour.

## 🚀 Fonctionnalités

- **Réponses fiables et sourcées :** L'agent extrait les passages les plus pertinents pour formuler sa réponse.
- **Zéro hallucination :** Si la réponse ne se trouve pas dans la documentation, l'agent reste spécialisé et refuse d'inventer.
- **Données dynamiques :** La base de connaissances est directement connectée et synchronisée à partir d'une source web externe.
- **Interface intuitive :** Développé avec une interface de chat moderne grâce à **Gradio**.

## 🛠️ Technologies utilisées

- **Langage :** Python 🐍
- **Interface Utilisateur :** Gradio
- **Architecture :** RAG (Retrieval-Augmented Generation)
- **Modèles :** via Hugging Face (sentence-transformers pour la recherche sémantique, modèle de langage pour la génération)

## 📂 Comment l'utiliser

1. Téléversez le fichier `copie_de_objectif_ia_atelier_code_03_09_2026.py` sur votre environnement ou serveur.
2. Lancez le script pour générer votre lien public Gradio.

## 🙏 Remerciements

Merci à **Guillaume** et à l'équipe **Machine Learnia** pour cette formation très concrète — construire et déployer un vrai assistant IA en une soirée, pas juste suivre des slides.
