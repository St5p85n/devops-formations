# Formation DevOps

Bienvenue dans le repository officiel de la **formation DevOps**.

Ce dépôt regroupe l'ensemble des cours, démonstrations, exercices, travaux pratiques, projets et ressources utilisés tout au long de la formation.

L'objectif est de construire progressivement une compréhension **théorique et pratique** des pratiques et outils DevOps, depuis la gestion du code source jusqu'à l'intégration continue, le déploiement, la conteneurisation, l'orchestration et la supervision des applications.

---

##  Objectifs de la formation

À la fin de cette formation, l'apprenant sera capable de :

* Comprendre la culture et les principes DevOps.
* Utiliser efficacement Linux dans un environnement de développement et de déploiement.
* Maîtriser Git et GitHub pour la gestion du code source.
* Conteneuriser une application avec Docker.
* Créer et gérer des images et conteneurs Docker.
* Mettre en place des pipelines CI/CD.
* Automatiser les tests et les déploiements.
* Comprendre et utiliser Kubernetes.
* Déployer et administrer des applications conteneurisées.
* Mettre en place des mécanismes de monitoring et de supervision.
* Centraliser et analyser les logs.
* Comprendre les principales pratiques DevSecOps.
* Découvrir les principes du Cloud Computing appliqués au DevOps.
* Mettre en œuvre une chaîne DevOps complète sur un projet réel.

---

## Parcours de formation

### 01 — Linux

Introduction à l'environnement Linux et aux commandes essentielles.

**Notions abordées :**

* Système de fichiers Linux
* Commandes essentielles
* Gestion des fichiers et répertoires
* Permissions
* Utilisateurs et groupes
* Processus
* Services
* Variables d'environnement
* Bash et scripts Shell
* Gestion des processus
* Réseau sous Linux

 [Accéder au module](./01-linux/)

---

### 02 — Git & GitHub

Gestion de versions et collaboration sur des projets logiciels.

**Notions abordées :**

* Git et contrôle de version
* Repository local et distant
* `git init`
* `git clone`
* `git add`
* `git commit`
* `git push`
* `git pull`
* Branches
* Merge
* Rebase
* Pull Requests
* Gestion des conflits
* GitHub
* GitHub Issues
* GitHub Actions

[Accéder au module](./02-git-github/)

---

### 03 — Docker

Conteneurisation des applications.

**Notions abordées :**

* Concepts de conteneurisation
* Images Docker
* Conteneurs
* Dockerfile
* Docker Hub
* Volumes
* Networks
* Docker Compose
* Variables d'environnement
* Multi-stage builds
* Bonnes pratiques Docker

 [Accéder au module](./03-docker/)

---

### 04 — CI/CD

Automatisation de l'intégration et du déploiement des applications.

**Notions abordées :**

* Intégration continue
* Livraison continue
* Déploiement continu
* Pipelines CI/CD
* GitHub Actions
* Tests automatisés
* Build automatisé
* Gestion des artefacts
* Déploiement automatisé

[Accéder au module](./04-ci-cd/)

---

### 05 — Kubernetes

Orchestration des applications conteneurisées.

**Notions abordées :**

* Architecture Kubernetes
* Cluster
* Nodes
* Pods
* Deployments
* Services
* ConfigMaps
* Secrets
* Volumes
* Namespaces
* Ingress
* Scaling
* Rolling updates

 [Accéder au module](./05-kubernetes/)

---

### 06 — Jenkins

Automatisation des processus CI/CD avec Jenkins.

**Notions abordées :**

* Installation de Jenkins
* Jobs
* Pipelines
* Jenkinsfile
* Agents
* Credentials
* Webhooks
* Intégration avec GitHub
* Build et déploiement automatisés

 [Accéder au module](./06-jenkins/)

---

### 07 — Monitoring

Surveillance et supervision des applications et infrastructures.

**Technologies :**

* Prometheus
* Grafana

**Notions abordées :**

* Métriques
* Monitoring
* Alertes
* Dashboards
* Exporters
* Prometheus
* Grafana

 [Accéder au module](./07-monitoring/)

---

### 08 — Logging

Centralisation et analyse des logs.

**Technologies :**

* Elasticsearch
* Logstash
* Kibana

**Notions abordées :**

* Logs applicatifs
* Centralisation
* Elasticsearch
* Logstash
* Kibana
* Recherche et analyse des logs
* Monitoring des applications

 [Accéder au module](./08-logging/)

---

### 09 — Cloud & DevOps

Introduction aux environnements Cloud et à leur utilisation dans une démarche DevOps.

**Notions abordées :**

* Cloud Computing
* Infrastructure as a Service
* Platform as a Service
* Déploiement dans le Cloud
* Infrastructure
* Sécurité
* Scalabilité
* Concepts AWS / Azure / GCP

 [Accéder au module](./09-cloud/)

---

# Projet final

La formation se termine par la réalisation d'un **projet DevOps complet**.

L'objectif sera de mettre en pratique les différentes technologies étudiées afin de construire une chaîne automatisée permettant de :

```text
Développement
     ↓
     Git
     ↓
    GitHub
     ↓
   CI/CD
     ↓
   Docker
     ↓
 Kubernetes
     ↓
 Déploiement
     ↓
 Monitoring
     ↓
   Logging
```

Le projet final permettra notamment de travailler sur :

* Git / GitHub
* Docker
* CI/CD
* Kubernetes
* Monitoring
* Logging
* automatisation
* déploiement

 [Accéder au projet final](./10-projet-final/)

---

# Technologies et outils

| Domaine          | Technologies                    |
| ---------------- | ------------------------------- |
| Système          | Linux                           |
| Versioning       | Git                             |
| Collaboration    | GitHub                          |
| Conteneurisation | Docker                          |
| CI/CD            | GitHub Actions, Jenkins         |
| Orchestration    | Kubernetes                      |
| Monitoring       | Prometheus, Grafana             |
| Logging          | Elasticsearch, Logstash, Kibana |
| Cloud            | AWS / Azure / GCP               |
| Scripting        | Bash                            |
| Automatisation   | CI/CD                           |

---

# Organisation du repository

```text
devops-formations/
│
├── README.md
│
├── 01-linux/
│   ├── README.md
│   ├── cours/
│   ├── exercices/
│   └── tp/
│
├── 02-git-github/
│   ├── README.md
│   ├── cours/
│   ├── exercices/
│   └── tp/
│
├── 03-docker/
│   ├── README.md
│   ├── cours/
│   ├── exercices/
│   └── tp/
│
├── 04-ci-cd/
│   ├── README.md
│   ├── github-actions/
│   └── tp/
│
├── 05-kubernetes/
│   ├── README.md
│   ├── manifests/
│   └── tp/
│
├── 06-jenkins/
│   ├── README.md
│   └── tp/
│
├── 07-monitoring/
│   ├── README.md
│   ├── prometheus/
│   └── grafana/
│
├── 08-logging/
│   ├── README.md
│   └── elk/
│
├── 09-cloud/
│   ├── README.md
│   └── exercices/
│
├── 10-projet-final/
│   ├── README.md
│   └── ...
│
└── resources/
    ├── commandes.md
    ├── bonnes-pratiques.md
    └── glossaire.md
```

---

# Méthode pédagogique

Chaque module peut être organisé autour de quatre parties :

### 1. Cours

Présentation des concepts théoriques et des notions fondamentales.

### 2. Exercices

Exercices progressifs permettant de vérifier la compréhension des notions.

### 3. Travaux pratiques

Mise en pratique des technologies dans des scénarios proches de situations professionnelles.

### 4. Projet

Application des connaissances sur un projet concret.

---

# Prérequis

Une connaissance de base en :

* programmation ;
* développement web ;
* bases de données ;
* réseaux ;
* systèmes d'exploitation ;

est recommandée.

Une familiarité avec Java, Spring Boot ou un autre framework backend peut également être utile pour certains travaux pratiques.

---

# Progression

La formation suit une progression allant des fondamentaux vers l'automatisation et le déploiement :

```text
Linux
  ↓
Git & GitHub
  ↓
Docker
  ↓
CI/CD
  ↓
Kubernetes
  ↓
Monitoring
  ↓
Logging
  ↓
Cloud
  ↓
Projet DevOps
```

---

# Ressources

Les ressources complémentaires seront ajoutées progressivement dans le dossier :

```text
resources/
```

On y retrouvera notamment :

* commandes utiles ;
* bonnes pratiques ;
* glossaire DevOps ;
* liens vers la documentation officielle ;
* fiches pratiques.

---

# Formation

**Formation : DevOps**

Repository pédagogique destiné à centraliser les supports, exercices, travaux pratiques et projets de la formation.

---

## Contribution

Les améliorations, corrections et propositions pédagogiques sont les bienvenues.

Pour contribuer :

1. Créer une branche.
2. Effectuer les modifications.
3. Créer un commit explicite.
4. Pousser la branche sur GitHub.
5. Créer une Pull Request.

---

## Licence

Ce repository est destiné à un usage pédagogique et de formation.

## Git Branches — Progression

Cette section est utilisée pour pratiquer le travail avec les branches Git.

- Création d'une branche
- Modification du code
- Commit
- Push
- Pull Request
- Merge
## Git Practice

Cette section est utilisée pour pratiquer les commandes Git avancées.