<!-- Filename: Help4.x:Templates:_Customise_Source  / Display title: Modèles : Personnaliser la Source  -->

<div class="alert alert-warning">
Cette page apparaît dans l'index des pages d'aide mais n'est pas utilisée via un bouton d'aide.
Il s'agit d'un bug qui sera probablement corrigé.
</div>

## Description

La page *Templates : Personnaliser la Source* est l'endroit où le code source des fichiers de modèle est modifié. Elle offre une interface en texte brut pour éditer les fichiers de modèle. La syntaxe de programmation HTML et PHP est mise en évidence pour rendre les fichiers de code source plus faciles à lire. Dans la barre de titre, le mot *Source* apparaît comme le nom du modèle, par exemple *(Cassiopeia)*.

## Comment Accéder

- Sélectionnez **Système → Panneau de modèles → Modèles de site** dans le menu de l'administrateur. Ou...
- Sélectionnez **Système → Panneau de modèles → Modèles d'administrateur** dans le menu de l'administrateur. Puis...
  - Sélectionnez un nom de modèle dans la colonne **Modèles**. Ensuite...
    - Sélectionnez un fichier à modifier dans l'onglet Éditeur.

## Capture d'écran

![Personnalisation des modèles avec l'onglet de l'éditeur de Cassiopeia](../../../fr/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)


## Champs de formulaire

### Onglet Éditeur

- Sélectionnez un fichier à éditer. La zone d'édition affiche du texte avec une syntaxe colorée pour la plupart des types de fichiers.

### Onglet Créer des remplacements

- Sélectionnez un élément à remplacer. Si un dossier est sélectionné, il est développé pour afficher une liste de fichiers. Si un fichier est sélectionné, il est immédiatement copié dans le dossier html sans demander de confirmation. Le remplacement est placé à l'emplacement approprié. Un message de confirmation s'affiche, par exemple : *Remplacement créé dans /templates/cassiopeia/html/mod_whosonline*.

### Onglet Fichiers mis à jour

Si aucune mise à jour n'a été apportée au modèle depuis la création des remplacements, cet onglet contiendra un simple message :

- **Avis** Les fichiers remplacés sont à jour. Rien n'a été changé lors de la dernière mise à jour de l'extension ou de Joomla.

Si des mises à jour ont eu lieu, un tableau affichera la liste des remplacements à réviser.

### Onglet Description du modèle

- **Vignette et Description** Informations sur ce modèle.

## Barre d'outils

Les icônes de la barre d'outils changent en fonction de l'action en cours. Vous pouvez voir :

- **Enregistrer** Enregistre l'élément et reste sur l'écran actuel.
- **Enregistrer et fermer** Enregistre l'élément et ferme l'écran actuel.
- **Copier le modèle** Copie le modèle actuel. Une boîte de dialogue
  demande un nouveau nom.
- **Aperçu du modèle** Sélectionnez pour ouvrir le site dans un nouvel onglet du navigateur.
- **Gérer les dossiers** Permet la création et la suppression de dossiers de modèles
  à l'aide d'une boîte de dialogue.
- **Nouveau fichier** Permet de télécharger un fichier depuis votre ordinateur vers
  la hiérarchie de fichiers du modèle à l'aide d'une boîte de dialogue.
- **Renommer le fichier** Sélectionnez un fichier à éditer. Sélectionnez le bouton Renommer pour
  demander un nouveau nom.
- **Supprimer le fichier** Vous serez invité à Confirmer ou Annuler.
- **Fermer le fichier** Ferme le fichier ouvert et retourne à l'onglet Éditeur.
- **Aide** Ouvre cet écran d'aide.

## Conseils

- Important : Ne supprimez pas les fichiers de modèle par défaut en utilisant FTP car cela génère une erreur à la fois sur le frontend et le backend.
- Avant de modifier le fichier HTML et CSS du modèle, il est judicieux de faire une sauvegarde du fichier que vous éditez. De plus, vous pouvez modifier ces fichiers en dehors de Joomla! en utilisant l'éditeur HTML ou CSS de votre choix.

*Traduit par openai.com*

