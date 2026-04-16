# TP3 – Agent IA avec Groq, mémoire et outils

## Objectif du projet

Ce projet a été réalisé dans le cadre du TP3 de Prompt Engineering et Agents IA.

L’objectif est de créer un agent intelligent capable de :
- répondre à des questions en langage naturel
- utiliser des outils externes (recherche web)
- garder une mémoire des échanges
- simuler un comportement de type RAG (Retrieval-Augmented Generation)

---

## Fonctionnalités

Ce projet contient :

- un agent basé sur le modèle Llama 3 (Groq)
- une mémoire simple (historique des messages)
- un outil de recherche via DuckDuckGo
- un système de contexte pour améliorer les réponses
- une structure proche d’un agent RAG simplifié

---

## Technologies utilisées

- Python
- Groq API
- DuckDuckGo Search
- Streamlit (optionnel)
- Google Colab

---

## Installation

Installer les dépendances :

```bash
pip install groq duckduckgo-search streamlit
