<!-- Filename: Help4.x:Components_Patch_Tester_Options  / Display title: Options de test de patch -->

## Description

Le *Joomla! Patch Tester* est utilisé par les testeurs pour vérifier que les patchs de code
produits par les développeurs font effectivement ce qu'ils sont censés faire sans
effets secondaires indésirables. La page *Options* est utilisée pour configurer la connexion Github.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

Plus d'informations : [Un guide pour les nuls sur les tests de bugs Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Comment accéder

- Sélectionnez **Composants → Testeur de Patch** dans le menu Administrateur.
  - Sélectionnez le bouton *Options* dans la barre d'outils.

## Capture d'écran

![Formulaire des options de Patchtester](../../../fr/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Champs de formulaire

### Onglet Dépôt GitHub

- **Dépôt GitHub** Le dépôt par défaut est `Joomla! CMS`. Utilisez-le.

### Onglet Authentification GitHub

Vous avez besoin d'un compte GitHub et d'un jeton GitHub. Tout est gratuit - consultez l'onglet Authentification GitHub pour plus de détails.

![Options Patchtester onglet d'authentification GitHub](../../../fr/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Méthode d'authentification GitHub** Choisissez la méthode du jeton. La méthode des identifiants ne fonctionnera plus à partir de septembre 2020.
- **Jeton GitHub** Collez le jeton obtenu sur GitHub.

### Onglet Paramètres du serveur CI

Ces paramètres sont utilisés pour les tests automatisés. Utilisez les valeurs par défaut pour les tests manuels.

![Options Patchtester onglet des paramètres du serveur CI](../../../fr/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Adresse du serveur CI** Par défaut : `https://ci.joomla.org`
- **Activer l'intégration CI** Par défaut : Désactivé

*Traduit par openai.com*

