# Rapport de déploiement - [SMITHIES Andrew]

## Liens
- **Application en ligne :** [[URL_SCALINGO](https://evaluation.osc-fr1.scalingo.io/)]
- **Dépôt de code :** [[URL_GITHUB](https://github.com/AndrewSmithiesDev/evaluation.git)]
## Prérequis techniques
* Symfony 8
* Composer installé
* PHP 8.4+
* Twig
* Un compte Scalingo

## Fichier de configuration CI
Le fichier de configuration de l'intégration continue se trouve dans : .github/workflows/ci.yaml

## Procédure de déploiement pas à pas
1. **Création :** Création d'une nouvelle application sur mon tableau de bord [Scalingo](Scalingo.com).
2. **Liaison :** Liaison de mon application à mon dépôt GitHub.
3. **Automatisme :** Activation des déploiements automatiques.
4. **Lancement :** Déclenchement du premier déploiement manuellement.
