<!-- Filename: Help4.x:Templates:_Customise / Display title: Templates : Personnaliser -->

## Description

La page *Templates : Personnaliser* est utilisée pour modifier le code source d'un template. Vous pouvez créer des surcharges pour les fichiers PHP et créer des fichiers user.css et user.js pour ajouter aux versions système. Vous pouvez également créer des templates enfants pour permettre la modification des fichiers maîtres du template surchargé.

## Comment accéder

- Sélectionnez **Système → Panneau des Templates → Templates du site** dans le menu Administrateur. Ou...
- Sélectionnez **Système → Panneau des Templates → Templates de l'administrateur** dans le menu Administrateur. Ensuite...
  - Sélectionnez un nom de template dans la colonne **Template**.

## Capture d'écran

Les écrans des Templates du site et des Templates de l'administrateur utilisent la même disposition. L'écran des Templates du site est illustré ici.

![personnalisation des templates onglet cassiopeia éditeur](../../../fr/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Champs de formulaire

### Onglet Éditeur

- Sélectionnez un fichier à modifier. La zone d'édition montre un texte avec une coloration syntaxique pour la plupart des types de fichiers.

### Onglet Créer des surcharges

![personnalisation des templates onglet cassiopeia créer des surcharges](../../../fr/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Sélectionnez un élément à surcharger. Les éléments marqués d'une icône de fichier plein s'ouvrent pour révéler une liste d'éléments. Les éléments marqués d'icônes de page superposées (ouverte et remplie) créent immédiatement une surcharge sans demander de confirmation. La surcharge est placée à l'emplacement approprié. Un message de confirmation apparaît, par exemple :
  *Surcharge créée dans /templates/cassiopeia/html/mod_whosonline*.

### Onglet Fichiers mis à jour

![personnalisation des templates onglet cassiopeia fichiers mis à jour](../../../fr/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Si aucune mise à jour du template n'a eu lieu depuis la création des surcharges, cet onglet contiendra un message simple :

<div class="alert alert-success">
Les fichiers surchargés sont à jour. Rien n'a été modifié
dans la dernière extension ou mise à jour de Joomla.
</div>

Si des mises à jour ont eu lieu, un tableau affichera une liste des surcharges à examiner.

### Onglet Description du template

![personnalisation des templates onglet cassiopeia description du template](../../../fr/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Vignette et description** Informations sur ce template.

## Barre d'outils

Notez que les boutons de la barre d'outils changent lorsqu'un fichier est sélectionné pour modification.

### Aucun fichier sélectionné

En haut de la page, vous verrez la barre d'outils affichée dans la capture d'écran ci-dessus. Les fonctions sont :

- **Créer un template enfant** Sélectionnez pour créer un nouveau template enfant complet. Il vous sera demandé de saisir un nom pour le nouveau template enfant. Vous avez également la possibilité de fermer sans créer de template enfant. Pour supprimer le nouveau template enfant : sélectionnez le bouton **Fermer**, sélectionnez le bouton Styles dans la barre d'outils de la liste des Templates, cochez la case du template enfant dans la liste et sélectionnez Supprimer dans la barre d'outils.
- **Aperçu du template** Sélectionnez pour ouvrir la vue par défaut du site en utilisant ce template.
- **Gérer les dossiers** Sélectionnez pour créer un nouveau dossier dans la hiérarchie du template. Une fenêtre contextuelle apparaît. **Important :** sélectionnez le dossier dans lequel le nouveau dossier doit apparaître avant de le créer.
- **Nouveau fichier** Sélectionnez pour créer un nouveau fichier ou pour télécharger un fichier depuis votre ordinateur dans la hiérarchie du template Joomla! Une fenêtre contextuelle apparaît. **Important :** Sélectionnez le dossier dans lequel le nouveau fichier doit apparaître avant de le créer.
- **Vérifier les surcharges** Activé lorsqu'une surcharge est sélectionnée dans l'onglet *Surcharges*. Les options sont :
  - Marquer comme vérifié
  - Marquer comme non vérifié
  - Supprimer l'enregistrement
- **Fermer** Ferme l'écran actuel et retourne à l'écran précédent sans enregistrer les modifications que vous avez pu apporter. Cet icône de la barre d'outils n'est pas affiché si vous créez un nouvel élément.
- **Aide** Ouvre cet écran d'aide.

### Fichier sélectionné

- **Enregistrer** Enregistre l'élément et reste dans l'écran actuel.
- **Enregistrer et fermer** Enregistre l'élément et ferme l'écran actuel.
- **Renommer le fichier** Sélectionnez un fichier à modifier. Sélectionnez le bouton Renommer pour entrer un nouveau nom.
- **Supprimer le fichier** Vous serez invité à confirmer ou annuler.
- **Vérifier les surcharges** Activé lorsqu'une surcharge est sélectionnée dans l'onglet *Surcharges*.
- **Fermer le fichier** Ferme le fichier ouvert et retourne à l'onglet Éditeur.
- **Aide** Ouvre cet écran d'aide.

## Conseils

- Avant de modifier le fichier HTML ou CSS du template, il est conseillé de faire une sauvegarde du fichier que vous modifiez. Vous pouvez également modifier ces fichiers en dehors de Joomla! en utilisant l'éditeur HTML ou CSS de votre choix.
