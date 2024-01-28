---
title: Projet Personnel
publishDate: 2019-12-01 00:00:00
img: /assets/Grafana.jpg
img_alt: Données
description: |
  Projet personnel sur l'exploitation des données de mon ordinateur
tags:
  - Grafana
  - Prometheus
  - Python
---

Mon projet actuel représente une exploration passionnante de plusieurs technologies que j'avais hâte de découvrir. L'idée maîtresse était d'utiliser Grafana pour visualiser les données de mon système. Pour ce faire, j'ai entrepris d'utiliser Prometheus et Windows Exporter afin de collecter des données précises sur les performances de mon ordinateur, telles que l'utilisation du CPU et de la mémoire.

L'intégration de Grafana a été un point central de ce projet, me permettant de créer des tableaux de bord dynamiques et informatifs à partir des données collectées. L'utilisation de PromQL a été essentielle pour formuler des requêtes spécifiques et extraire des informations cruciales sur le fonctionnement de mon système.

Lors de l'intégration du Windows Exporter j'ai dû configurer quelques fichiers notamment le .yml de Prometheus pour y ajouter le job Windows Exporter, assurant ainsi la récupération réussie des données.

Un aspect clé de ce projet a été l'implémentation d'un script Python personnalisé. Ce script effectue des requêtes PromQL sur l'utilisation du CPU, et en cas de dépassement d'un certain pourcentage prédéfini, il déclenche l'envoi d'un e-mail d'alerte. Cette fonctionnalité m'a permis de rester informé en temps réel des variations de performances de mon système.

Actuellement, le projet est en cours, et la prochaine étape que j'ai envisagée est d'intégrer Jenkins pour automatiser le processus de collecte de données à intervalles réguliers. Cette approche périodique rendra le système plus réactif et permettra une surveillance continue sans nécessiter d'interventions manuelles.