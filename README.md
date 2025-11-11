# stock_manager_final
# 🏪 Gestionnaire de Stock

![Python Tests](https://github.com/diams45588/stock_manager_final/actions/workflows/python-tests.yml/badge.svg)

Système de gestion de stock avec tests automatisés et intégration continue.

## 🚀 Fonctionnalités

- Gestion des produits (CRUD)
- Calcul automatique du stock total
- Tests unitaires complets
- Intégration continue avec GitHub Actions

## 🧪 Tests

Les tests s'exécutent automatiquement sur GitHub Actions à chaque push.

### Exécution locale

```bash
pip install -r requirements.txt
python init.py
python -m unittest discover tests -v