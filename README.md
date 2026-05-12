# Mady.IA — Evaluation d'agent IA

Mady.IA est un outil no-code qui permet de **tester, évaluer et améliorer des agents IA**.  
Il génère automatiquement des scénarios de test, évalue les réponses selon des critères adaptés au type d’agent, et propose des recommandations d’amélioration.

Projet réalisé dans le cadre du Hackathon IA 2026.

---

## Fonctionnalités

- Génération automatique de tests (nominal, limite, critique)
- Détection du type d’agent IA
- Évaluation intelligente basée sur des critères adaptés
- Simulation d’agents (robuste / hors-sujet)
- Radar de performance + scores détaillés
- Recommandations d’amélioration
- Export de rapport PDF

---

## Installation

### 1. Cloner le projet
```bash
git clone https://github.com/ton-compte/mady-ai.git
cd mady-ai
```

### 2. Installer les dépendances
```bash
pip install streamlit mistralai matplotlib numpy reportlab pytest
```

### 3. Lancer l’application
```bash
streamlit run app.py
```

## Configuration

**Le projet utilise l’API Mistral AI.**

Ajouter votre clé API dans engine.py :

```bash
MISTRAL_API_KEY = "votre_cle_api"
```
