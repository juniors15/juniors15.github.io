---
layout: page
title: "Marche à suivre GitHub sur Visual Studio Code"
permalink: /tm_2026/mas_VS_GH/
---
# Marche à suivre pour créer un dossier et le mettre sur GitHub

## 1. Ouvrir un dossier pour démarrer un nouveau projet

- Ouvrir **Visual Studio Code**
- Cliquer sur **Fichier > Ouvrir un dossier**
- Sélectionner ou créer un dossier vide (ex. `mon-projet`)
- Cliquer sur **Ouvrir**

## 2. Initialiser un projet Git dans VS Code

### Méthode graphique (recommandée)

- Dans la barre latérale gauche, cliquer sur l’icône **Source Control**
- *(Windows uniquement)* : installer **Git for Windows** si nécessaire
- Cliquer sur **Initialize Repository**

➡️ Le dépôt Git est maintenant créé localement.

## 3. Se connecter à GitHub depuis Visual Studio Code

- En bas à gauche de VS Code, cliquer sur l’icône **Compte (👤)**
- Cliquer sur **Sign in to GitHub**
- Le navigateur s’ouvre
- Se connecter à GitHub et autoriser Visual Studio Code

➡️ VS Code est maintenant lié à votre compte GitHub.

## 3.2 Si en cliquant sur l'icône **compte**, vous ne pouvez pas vous connecter.

- Cliquer sur **Code** (tout en haut à gauche)
- Cliquer sur **Réglages**
- Service en ligne
- Se Connecter
- Connexion à Github

## 4. Créer le dépôt GitHub distant

- Ouvrir **Source Control**
- Cliquer sur **Publish Branch**
- Choisir **Public** ou **Private**

➡️ Le projet est maintenant visible sur GitHub.

## 5. Ajouter des fichiers au projet

- Créer un fichier (ex. `README.md`)
- Sauvegarder le fichier
- Le fichier apparaît dans **Changes**

## 6. Add – Ajouter les fichiers

- Cliquer sur le **+** à côté des fichiers

## 7. Commit – Enregistrer les changements

- Écrire un message de commit (ex. *Premier commit*)
- Cliquer sur **Commit**

## 8. Push – Envoyer vers GitHub

- Cliquer sur **Sync Changes** ou **Push**

## Résumé du cycle Git

Modifier → Add → Commit → Push → Pull

## Problème possible

Si Git demande une identité :

```bash
git config --global user.email "email_du_compte_github"
git config --global user.name "le_nom_que_vous_voulez"
```
