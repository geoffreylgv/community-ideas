# Contribuer à Community Ideas

Merci de vouloir contribuer à Community Ideas !

Ce guide explique comment contribuer au projet avec Git et GitHub.

## 1. Prérequis

Avant de commencer, assurez-vous d'avoir :

* Un [compte GitHub](https://github.com/).
* [Git](https://git-scm.com/downloads) installé sur votre ordinateur.
* Un terminal ou une interface en ligne de commande.

Vérifiez que Git est installé :

```bash
git --version
```

## 2. Configurer Git

Si vous n'avez jamais utilisé Git sur votre ordinateur, configurez votre nom et votre adresse e-mail :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre-email@example.com"
```

Utilisez le nom et l'adresse e-mail que vous souhaitez associer à vos commits.

## 3. Faire un fork du dépôt

1. Ouvrez le dépôt Community Ideas sur GitHub.
2. Cliquez sur **Fork**.
3. Créez une copie du dépôt sur votre compte GitHub.

Votre fork est votre copie personnelle du projet. Vous pouvez y apporter des modifications sans modifier directement le dépôt original.

## 4. Cloner votre fork

Remplacez `VOTRE-USERNAME` par votre nom d'utilisateur GitHub :

```bash
git clone https://github.com/VOTRE-USERNAME/community-ideas.git
cd community-ideas
```

## 5. Créer une branche

Créez une branche dédiée à votre contribution :

```bash
git switch -c add/ma-contribution
```

Choisissez un nom explicite, par exemple :

```bash
git switch -c add/idee-atelier-python
```

## 6. Faire vos modifications

Ouvrez le dossier du projet dans votre éditeur préféré.

Par exemple, avec Visual Studio Code :

```bash
code .
```

Effectuez vos modifications localement. Vous pouvez ajouter une idée, améliorer la documentation, corriger une erreur ou proposer une amélioration.

Avant de continuer, vérifiez vos changements :

```bash
git status
git diff
```

## 7. Ajouter et enregistrer vos modifications

Préparez les fichiers à inclure dans votre commit :

```bash
git add .
```

Créez un commit avec un message explicite :

```bash
git commit -m "Add a Python workshop idea"
```

Un commit enregistre vos modifications localement.

## 8. Envoyer votre branche sur GitHub

Poussez votre branche vers votre fork :

```bash
git push -u origin add/ma-contribution
```

Si vous avez utilisé un autre nom de branche, remplacez `add/ma-contribution` par le nom réel de votre branche.

Vos modifications sont maintenant disponibles sur votre fork GitHub.

## 9. Ouvrir une Pull Request

1. Ouvrez votre fork sur GitHub.
2. Cliquez sur **Compare & pull request**, ou utilisez la suggestion affichée après le push.
3. Vérifiez que le dépôt de destination est le dépôt original Community Ideas.
4. Ajoutez un titre explicite et décrivez vos modifications.
5. Soumettez votre Pull Request.

Les responsables du projet examineront votre contribution et pourront demander des modifications avant de la fusionner.

## 10. Si des modifications sont demandées

Si les responsables demandent des changements, modifiez vos fichiers localement puis exécutez :

```bash
git add .
git commit -m "Update contribution based on feedback"
git push
```

Votre Pull Request existante sera mise à jour automatiquement.

## Points importants

* Ne poussez pas directement vers le dépôt original, sauf si vous disposez explicitement des droits d'écriture et que cela vous a été demandé.
* N'ajoutez jamais de mots de passe, clés API, jetons ou autres informations secrètes dans le dépôt.
* Limitez votre contribution à un objectif clair et utilisez des messages de commit explicites.
* Vous pouvez contribuer en français ou en anglais.
* L'ouverture d'une Pull Request ne garantit pas qu'elle sera fusionnée.

Merci de contribuer à construire notre communauté !