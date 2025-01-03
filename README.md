# Challenge QA - Playwright Tests

Ce projet contient des tests automatisés utilisant Playwright pour tester des formulaires de création de profil utilisateur. Il est configuré avec GitHub Actions pour l'exécution des tests en continu.

## I. Premièr Module du challenge

La première partie du challenge est détaillée dans un fichier PDF (Module 1 UI Testing ) qui se trouve à la racine du projet.

### II. Deuxieme Module du challenge

Ce projet contient des tests automatisés utilisant Playwright pour tester des formulaires de création de profil utilisateur. Il est configuré avec GitHub Actions pour l'exécution des tests en continu.


### 1. Plan de test

Le plan de test détaillé est disponible dans le dossier `planDeTest`.

## Étapes

### 1. Cloner le projet

Clonez le projet depuis GitHub :

```bash
git clone https://github.com/igorvannel/challengeQA.git
cd challengeQA
```
### 2. Installer les dépendances
Avant de commencer, assurez-vous d'avoir Node.js installé sur votre machine. Vous pouvez vérifier si Node.js est installé avec la commande suivante :

```bash
Copier le code
node -v
```
Si Node.js n'est pas installé, vous pouvez le télécharger et l'installer depuis le site officiel : Node.js.

Ensuite, pour installer les dépendances nécessaires au projet, exécutez la commande suivante :

```bash
Copier le code
npm ci
```
### 3. Exécuter les tests localement
Pour exécuter les tests avec Playwright, vous devez d'abord installer les navigateurs nécessaires. Utilisez la commande suivante pour installer Playwright avec ses dépendances :

```bash
Copier le code
npx playwright install --with-deps
```
Cette commande téléchargera et installera les navigateurs nécessaires à Playwright pour l'exécution des tests.

### 4. Lancer les tests
Une fois les dépendances et les navigateurs installés, vous pouvez exécuter les tests avec la commande suivante :

```bash
Copier le code
npm run test
```
Vous pouvez également accéder au rapport en ouvrant le fichier test-results/index.html dans votre navigateur local.

### 4. Exécution des tests via GitHub Actions

Le projet est configuré avec GitHub Actions pour exécuter les tests automatiquement à chaque push ou pull request sur la branche main ou master.

Les tests sont exécutés sur un environnement Ubuntu et configurés dans le fichier .github/workflows/ci.yml.
