# Dashboard Financier PME — CôteAzur Boutique Hotel

## Le problème
Les dirigeants de PME manquent d'outils simples pour piloter
leur performance financière en temps réel — ils naviguent
souvent à vue sans indicateurs clairs ni prévisions.

## La solution
Dashboard financier complet sur 2 ans de données avec
visualisations interactives, analyse des charges et
forecast automatique du CA pour l'année suivante.

## Indicateurs clés

| Métrique | Valeur |
|---------|--------|
| CA total 2023-2024 | 4 011 875 € |
| Marge brute moyenne | 17.3% |
| Trésorerie finale | 722 858 € |
| Forecast CA 2025 | 2 104 864 € |
| Croissance estimée | +4.9% |

## Visualisations

- 📊 **Evolution CA & Charges** — comparaison mensuelle sur 2 ans
- 💰 **Trésorerie cumulée** — suivi de la santé financière
- 🥧 **Répartition des charges** — identification des postes clés
- 🔮 **Forecast 2025** — projection basée sur tendance + saisonnalité

## Insights business

- **Personnel = 42.6% des charges** — premier levier d'optimisation
- **Marge estivale 22%** vs **marge hivernale 13%** — forte saisonnalité
- **Energie = 9.72%** — potentiel d'économies avec investissements verts
- **Croissance +4.9%** confirmée par la tendance historique

## Stack technique
- **Python** — Pandas, NumPy, Plotly, SciPy
- **Modélisation** — Régression linéaire + saisonnalité
- **Visualisation** — 4 graphiques interactifs Plotly

## Structure du projet
- data/finance_pme.csv — 24 mois de données financières
- notebooks/01_generation_donnees.ipynb — Génération des données
- notebooks/02_dashboard_visualisations.ipynb — Dashboard & forecast

---
*Projet réalisé par [ClearInsightdata]
(https://github.com/clearinsightdata)*