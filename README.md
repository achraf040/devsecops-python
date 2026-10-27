# Mini-projet DevSecOps Python

Ce mini-projet illustre la mise en œuvre d’un pipeline **CI/CD DevSecOps** complet avec GitHub Actions.

## Étapes du pipeline
1. **Build** → Installation des dépendances.
2. **Test** → Exécution des tests unitaires (Pytest).
3. **Scan** → Analyse des vulnérabilités avec Trivy.
4. **Deploy** → Déploiement simulé sur un environnement de staging.

## Exécution locale
```bash
pip install -r requirements.txt
pytest -v
