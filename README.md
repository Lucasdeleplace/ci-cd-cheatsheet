# GitHub Actions (CI/CD) Cheatsheet

## Table des matières
  - [1.1 Introduction](#11-introduction)
     - [1.1.1 Planification](#111-planification)
     - [1.1.2 Préparation et Cuisson](#112-préparation-et-cuisson)
     - [1.1.3 Dressage](#113-dressage)
     - [1.1.4 Service](#114-service)
  - [1.2 Les outils CI/CD](#12-les-outils-ci-cd)
     - [1.2.1 Gestion des versions](#121-gestion-des-versions)
     - [1.2.2 Serveurs d'intégration continue (CI)](#122-serveurs-dintégration-continue-ci)
---

## 1.1 Introduction

*Métaphore utilisée : grand repas de famille*

Comme dans un repas, **plusieurs** étapes : 

### 1.1.1 Planification

| Étape | Côté Restaurant | Côté Développement |
|-------|-----------------|-------------------|
| Planification | Liste de courses détaillée | - Utilisation de Jira/Trello<br>- Création de tickets<br>- Planification méticuleuse des tâches |

### 1.1.2 Préparation et Cuisson

| Étape | Côté Restaurant | Côté Développement |
|-------|-----------------|-------------------|
| Préparation et Cuisson | - Cœur de l'activité<br>- Mélange des ingrédients selon la recette | Intégration Continue (CI)<br>- Intégration de chaque commit dans la branche principale |

    ### 1.1.3 Dressage

| Étape | Côté Restaurant | Côté Développement |
|-------|-----------------|-------------------|
| Dressage | - Décoration de la production<br>- Préparation de la cuisine | Livraison Continue (CD)<br>- Déploiement de chaque commit en production |

### 1.1.4 Service

| Étape | Côté Restaurant | Côté Développement |
|-------|-----------------|-------------------|
| Service | - Service aux invités<br>- Dégustation de la cuisine | Déploiement Continu (CD)<br>- Déploiement de chaque commit en production |

---
## 1.2 Les outils CI/CD

CI/CD = au coeur du DevOps
- Automatisation des compilation, tests, déploiement

### 1.2.1 Gestion des versions

Versionning = gestion des versions -> essentielle pour suivre les modifications, et permet aux équipes de collaborer efficacement

- **Git** : système de gestion de versionning **décentralisé**
- **Subversion** (SVN) : Outil de gestion de versionning **centralisé**
- **Mercurial** : système de gestion de versionning **distribué**

### 1.2.2 Serveurs d'intégration continue (CI)

Serveurs d'intégration continue = systèmes automatisés jouant un rôle crucial dans le dev' logiciel moderne.
**Fonction principale** : compilation automatique dès qu'un commit est effectué

**Les serveurs CI** : souvent des conteneurs / machines virtuelles (environnement isolé) -> garantie que l'exécution des tests est propre et contrôlée

<!-- Intégrer les liens de site officiel de chaque outil -->
- **Jenkins** ([ici](https://www.jenkins.io/)) : outil open source de CI/CD
- **Gitlab CI** ([ici](https://docs.gitlab.com/ee/ci/)) : outil de CI/CD **intégré** par Gitlab
- **Github Actions** ([ici](https://docs.github.com/en/actions)) : outil de CI/CD **intégré** à Github
- **CircleCI** ([ici](https://circleci.com/)) : outil de CI/CD pour le développement de logiciel
- **TravisCI** ([ici](https://www.travis-ci.com/)) : outil de CI/CD pour construire et tester des projets 

