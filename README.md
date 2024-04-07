# Projet Docker Machine Learning

Ce dépôt contient les fichiers et instructions pour réaliser un projet utilisant Docker et Vagrant pour créer un environnement de développement isolé pour exécuter des algorithmes de machine/deep learning sur un dataset et afficher les résultats dans une interface web.

## Exercice 1: Algorithmes de Machine/Deep Learning

Dans cet exercice, je fais un  service nommé "algo_container" contenant un container Docker pour exécuter des algorithmes de machine/deep learning sur un dataset. Utilisez le langage de programmation Python, et réutilisez les algorithmes réalisés sur la dataset de WDBC.

## Exercice 2: Interface Web

Dans cet exercice, je fais un service nommé "ui_container" contenant un container Docker pour afficher les résultats obtenus à partir de "algo_container" dans une interface web. langage/serveur web: (HTML, CSS ,JavaScript, Flask, etc.).

## Exercice 3: Configuration de l'Environnement de Développement avec Vagrant

Dans cet exercice, j'ai configuré un environnement de développement virtuel Vagrant pour inclure les deux containers Docker créés dans les exercices 1 et 2. Cela permet d'isoler l'environnement de développement et d'automatiser les compilations.

## Exercice 4: Docker Compose / Swarm

Dans cet exercice, Docker Compose /Swarm  pour créer un nouveau répertoire nommé "version-image", contenant le fichier docker-compose.yml. Les services sont de type images (pas de build) des deux conteneurs créés dans les exercices 1 et 2.

---

### Instructions d'Utilisation

Pour utiliser ce projet, suivez les étapes suivantes :

1. Cloner ce dépôt sur votre machine locale.

2. Suivez les instructions spécifiques à chaque exercice dans leur répertoire respectif.

3. Pour utiliser Vagrant, assurez-vous d'avoir Vagrant installé sur votre machine. Exécutez ensuite les commandes spécifiées dans le répertoire "vagrant" pour créer et démarrer l'environnement.

4. Pour Docker Compose / Swarm, assurez-vous d'avoir Docker installé sur votre machine. Exécutez ensuite les commandes spécifiées dans le répertoire "version-image" pour démarrer les services.

---

### Auteur

- darza tarak
- https://github.com/tarakdarza
- Développeur principal


