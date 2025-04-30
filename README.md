# SonarQube Lab

## Introduction
SonarQube est une plateforme d’analyse de la qualité du code qui permet aux développeurs de détecter et corriger les problèmes de code tels que les bugs, les vulnérabilités, les mauvaises pratiques de codage et les problèmes de maintenabilité. SonarQube évalue plusieurs aspects du code source pour garantir qu'il est de haute qualité et sécurisé. Ce fichier explore brièvement trois concepts clés dans SonarQube : la qualité du logiciel, la sévérité des problèmes et les attributs du code propre.

## Software Quality (Qualité du Logiciel)
La **qualité du logiciel** dans SonarQube est une mesure globale qui englobe plusieurs critères, tels que :

- **La fiabilité** : Mesure de la stabilité du code. Un code fiable doit être exempt de bogues qui pourraient compromettre son fonctionnement.
- **La sécurité** : Détection des vulnérabilités qui pourraient être exploitées par des attaquants.
- **La maintenabilité** : Mesure de la facilité avec laquelle le code peut être modifié ou étendu sans introduire de nouveaux bugs ou problèmes.
- **La performance** : Bien que SonarQube ne se concentre pas directement sur la performance, des métriques liées à la performance (comme l'optimisation du code) peuvent être détectées dans le cadre des problèmes de maintenabilité.

SonarQube aide à surveiller ces aspects à travers des métriques détaillées et des indicateurs visuels, permettant aux équipes de développement de maintenir une haute qualité de code tout au long du cycle de vie du projet.

## Severity (Sévérité)
La **sévérité** est une classification des problèmes détectés dans le code selon leur impact potentiel. SonarQube classe les problèmes en plusieurs niveaux de sévérité :

1. **Blocker (Bloquant)** : Ce sont des problèmes graves qui empêchent le bon fonctionnement du logiciel ou qui présentent un risque de sécurité immédiat. Ils nécessitent une attention immédiate.
2. **Critical (Critique)** : Ce sont des problèmes majeurs qui peuvent affecter la stabilité ou la sécurité du logiciel. Ils doivent être corrigés rapidement.
3. **Major (Majeur)** : Problèmes importants, mais qui n'ont pas d'impact immédiat sur le fonctionnement du système. Ils doivent être résolus, mais peuvent être traités après les problèmes critiques.
4. **Minor (Mineur)** : Problèmes qui n'affectent pas directement la fonctionnalité du logiciel, mais qui peuvent nuire à la lisibilité ou à la maintenabilité du code.
5. **Info (Information)** : Ce sont des problèmes de moindre importance qui ne nécessitent généralement pas de correction immédiate mais peuvent améliorer la qualité globale du code.

La gestion de la sévérité permet de prioriser les efforts de correction, en se concentrant sur les problèmes les plus graves avant de passer aux problèmes mineurs.

## Clean Code Attributes (Attributs du Code Propre)
Un **code propre** est essentiel pour la maintenabilité à long terme. SonarQube évalue plusieurs attributs pour déterminer la propreté du code :

- **Lisibilité** : Le code doit être facilement compréhensible par les autres développeurs. Il doit suivre des conventions de nommage claires et avoir une structure logique.
- **Simplicité** : Un code simple est plus facile à comprendre et à maintenir. Les solutions complexes et redondantes doivent être évitées.
- **Modularité** : Le code doit être organisé en modules bien définis, chacun ayant une responsabilité claire et distincte.
- **Absence de duplication** : La duplication de code est un signe de mauvais design et augmente la complexité du projet. Le code doit être réutilisé là où cela est possible.
- **Tests** : Un code propre est accompagné de tests unitaires et d’intégration adéquats. SonarQube évalue également la couverture de tests pour garantir que le code fonctionne comme prévu.

Les **attributs du code propre** sont évalués à l’aide de différentes métriques, telles que la complexité, la duplication et la couverture des tests, afin de s'assurer que le code reste lisible, compréhensible et facile à maintenir.

## Visualisation des Résultats SonarQube

#### Génération du token
![Capture d'écran SonarQube - Rapport](screens\4.png)

#### Création du token pour envoyer les résultats au serveur SonarQube.
![Capture d'écran SonarQube - Rapport](screens\1.png)

#### Ajout du token
![Capture d'écran SonarQube - Rapport](screens\3.png)

#### Pipeline modifiée
![Capture d'écran SonarQube - Rapport](screens\5.png)

#### Résultat du pipeline
![Capture d'écran SonarQube - Rapport](screens\6.png)

#### Analyse de Sonarqube
![Capture d'écran SonarQube - Rapport](screens\7.png)

## Conclusion
SonarQube est un outil puissant pour évaluer la qualité du code et garantir que les logiciels développés respectent des normes de fiabilité, de sécurité et de maintenabilité. Grâce à des analyses détaillées des problèmes de code, des mesures de couverture et des vérifications de qualité, SonarQube aide les équipes à produire un code propre, sûr et performant. Utiliser SonarQube permet non seulement de corriger les erreurs avant qu'elles ne deviennent des problèmes majeurs, mais aussi de maintenir un niveau de qualité élevé tout au long du cycle de vie du projet.

