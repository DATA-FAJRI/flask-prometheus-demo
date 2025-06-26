# flask-prometheus-demo
# L'objectif est de prendre une simple application Flask et créer un point de terminaison pour étudier son activité
Ce projet est une petite application web en Python avec Flask qui expose des métriques pour Prometheus

Il montre comment :
- Créer une route `/` qui simule du travail
- Compter les requêtes avec `Counter`
- Mesurer la durée des requêtes avec `Histogram`
- Exposer les métriques sur `/my_metrics`

---

## Comment faire fonctionner le projet

### 1. Cloner ce dépôt


git clone https://github.com/DATA-FAJRI/flask-prometheus-demo.git
cd flask-prometheus-demo
